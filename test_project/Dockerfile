FROM python

ENV PYTHONUNBUFFERED 1

WORKDIR /newapp

ADD . /newapp

COPY ./requirements.txt /newapp/requirements.txt

RUN pip install -r requirements.txt

COPY . /newapp
