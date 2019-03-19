#Base
FROM python:3

#Env
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN mkdir /code
WORKDIR /code
#Pip
RUN pip install pip -U
ADD requirements.txt /code/
RUN pip install -r requirements.txt
ADD . /code/


