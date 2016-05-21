# flask-alpine
Minimal python alpine image to adduser and run a simple flask server

## This example creates a non-root user and runs a flask server

## Build using:
docker build --no-cache  -t python-build:latest .

## Run using:
docker run -it --name flaskpython -p 8008:8008 python-build:latest
