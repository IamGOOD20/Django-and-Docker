FROM python:3.12
#FROM python:3.8.7-slim-buster

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

WORKDIR /code

COPY ./req.txt /code/req.txt

#RUN apt-get update && apt-get -y install libpq-dev gcc && pip install psycopg2 \

RUN pip install -r /code/req.txt

COPY . /code
