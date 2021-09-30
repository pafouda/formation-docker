FROM ubuntu:bionic
RUN apt-get update
RUN apt-get install -y git
RUN apt-get install -y python3
FROM python:3
WORKDIR /usr/src/app
COPY . .
CMD ["hello.py"]
ENTRYPOINT ["python3"]