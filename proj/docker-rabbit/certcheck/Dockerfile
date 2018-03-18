FROM python:2.7
MAINTAINER CT

RUN apt-get update && apt-get install -y libpq-dev libffi-dev libsasl2-dev libldap2-dev
COPY ./requirements.txt /certcheck/requirements.txt
RUN pip install -r ./certcheck/requirements.txt

COPY ./ /

