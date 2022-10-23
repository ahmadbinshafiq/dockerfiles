FROM python:3

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

COPY requirements.txt /tmp
WORKDIR /tmp

RUN pip install -r requirements.txt

WORKDIR /code
COPY . /code/
