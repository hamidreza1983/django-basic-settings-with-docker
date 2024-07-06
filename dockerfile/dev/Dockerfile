FROM python:3.9
LABEL maintainer="hamidreza"

ENV PYTHONUNBUFFERED=1
ENV PYTHONDONTWRITEBYTECODE=1

WORKDIR /usr/src/app

COPY ./requirements.txt .
COPY ./core .

RUN pip install --upgrade pip && pip install -r requirements.txt