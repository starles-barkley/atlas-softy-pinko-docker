FROM ubuntu:latest
RUN apt-get update && \
	apt-get upgrade -y
RUN apt-get install -y python3, Python3-pip, and Flask
RUN pip3 install flask
COPY api.py /app/api.py
