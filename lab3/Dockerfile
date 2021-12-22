FROM ubuntu:20.04

RUN apt-get update
RUN apt-get install -y  python3
RUN apt-get install -y python3-pip
RUN pip3 install Flask

COPY hello.py hello.py
EXPOSE 5000
CMD ["python3", "hello.py"]

