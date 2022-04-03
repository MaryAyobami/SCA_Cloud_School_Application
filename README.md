# Title
A Flask App with Docker

## Introduction
This repository contains a dockerfile which displays  a web page made with Flask- a framework of python  . This project was created specifically for SheCodeAfrica Cloud School Application Assessment.

## Technologies
This project was created with:
* Python 3.8
* Flask
* HTML
* Docker

## Documentation on how this project was made
* Installation of packages in requirements.txt

with the command :   ``` pip install flask ```
* Creation of the App
* Creation of Dockerfile
* Building Docker image
 
The docker image was built with the command :
  ```
  docker image build -t flask_docker .
  ```
* Running the container

```
docker run -p 5000:5000 -d flask_docker
  ```
  
* Deploying to Docker hub
```
docker tag flask_docker maryayobami/flask-docker
```
```
docker push maryayobami/flask-docker
```



## Link to docker hub repository:
https://hub.docker.com/repository/docker/maryayobami/flask_docker
