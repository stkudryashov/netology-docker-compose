FROM python:3.9

RUN apt-get update

WORKDIR /usr/src/app/django_app
COPY . .
RUN pip install -r requirements.txt
