# Video Streaming Service

This application/microservice is based on this tutorial: https://github.com/bootstrapping-microservices

The application name is FlixTube. It is an application for video streaming, uploading, and storing videos.

### Run Normally:

Before running install dependencies:
```bash
    npm install
```

To start the microservice:
```bash
    node index.js
```

Or 
```bash
    npm start
```

Then point your browser at http://localhost:3000/video

### Building the docker image
```bash
docker build -t video-streaming --file Dockerfile .
```

### Running the container from my Azure Container Registry
```bash
docker run -d -p 3000:3000 --name my-video-streaming pomregist1.azurecr.io/video-streaming:latest
```
Then use this command to see the url of the application
```bash
docker logs my-video-streaming
```
