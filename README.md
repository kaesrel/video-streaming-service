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
* insert a document based on the contents in `db-fixture/videos.json`

Point browser to http://localhost:4002/video?id=5d9e690ad76fe06a3d7ae416
