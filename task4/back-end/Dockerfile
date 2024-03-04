FROM ubuntu:latest
WORKDIR /app
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install python3 -y
RUN apt-get install python3-pip -y
RUN pip3 install flask
RUN pip3 install flask-cors
COPY api.py ./
CMD ["python3", "./api.py"]