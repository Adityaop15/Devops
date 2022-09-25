FROM ubuntu:latest

RUN apt-get update 

RUN apt-get install python3 -y

RUN mkdir /app

COPY ./hello.py /app/hello.py

WORKDIR /app

CMD ["python3", "hello.py"]
