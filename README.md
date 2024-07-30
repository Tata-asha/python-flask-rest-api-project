## 1. Build Docker image 
docker build -t python-rest-api .

## 2. Run Docker image
docker run -p 9001:9001 python-rest-api

## 3.Build and Tag according to Dockerhub
docker tag soontobedevopsengineer/python-flask-rest-api-project:helm

## 4.Docker push
docker push soontobedevopsengineer/python-flask-rest-api-project:helm

## 5.Docker pull
docker pull  soontobedevopsengineer/python-flask-rest-api-project:helm

## 6.Run docker image
docker run -p 9001:9001 helm

