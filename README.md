# Bootstrap Basic Node App with VS Code Docker Extension

Demo for "Did you know?" section of Deloitte Digital Monday Huddle

## Installation

Use npm to install Express

```bash
npm install 
```

## Build Image

Using the -t flag to tag your image, build the Docker image

```bash
docker build -t <your username>/node-web-app .
```

Ensure you image is available by listing your images 

```bash
docker images
```

## Run the Image

Run the image in detached mode using  ```-d``` and publish the image using the ```-p``` flag

```bash 
docker run -p 49160:8080 -d <your username>/node-web-app
```

Ensure you container is running by listing your containers 

```bash
docker ps
```

## Resources
- [Become a Docker Power User using Visual Studio Code Talk](https://www.youtube.com/watch?v=sUZxIWDUicA&feature=emb_title)
- [Related Repo](https://github.com/vegasbrianc/vscode-docker-demo)