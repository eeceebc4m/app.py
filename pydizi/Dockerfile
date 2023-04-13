FROM ubuntu:20.04
WORKDIR /app
RUN apt-get update
RUN apt-get install -y python3-pip
RUN pip3 install flask
COPY app.py app.py

EXPOSE 80
CMD ["python3","app.py"]