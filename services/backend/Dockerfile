FROM python:3.9-buster

RUN mkdir app
WORKDIR /app

ENV path="${PATH}:/root/.local/bin"
ENV PYTHONPATH=.

COPY requirements.txt .
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

COPY migrations .
COPY aerich.ini .

COPY src/ .