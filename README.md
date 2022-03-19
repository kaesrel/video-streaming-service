# Video Streaming Service

This application/microservice is based on this tutorial: https://github.com/bootstrapping-microservices

The application name is FlixTube. It is an application for video streaming, uploading, and storing videos.


### Running Docker Compose
```bash
docker-compose down && docker-compose up --build
```
Stop the application:
```bash
docker-compose down
```
Use Robo 3T to 
* Create connection to localhost:4000
* create a new database called video-streaming
* create a collection called videos

Point browser to http://localhost:4001/video

Also point browser to http://localhost:15672/ and then:
* Username: `guest`
* Password: `guest`
