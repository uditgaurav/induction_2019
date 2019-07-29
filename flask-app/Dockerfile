FROM ubuntu:latest
RUN mkdir app
COPY . /app
WORKDIR /app
RUN apt-get update -y && apt-get install -y python-pip python-dev build-essential && pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
