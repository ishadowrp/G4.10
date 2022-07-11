FROM python:3.9.0

WORKDIR /backend

ADD requirements.txt /backend/requirements.txt

RUN pip install -r requirements.txt

ADD . /backend/

ENV PYTHONPATH /backend

EXPOSE 8000