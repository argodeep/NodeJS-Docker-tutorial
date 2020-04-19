# NodejS-Docker-tutorial

## Build Image
docker build -t nodejs-app .

## Run the App (Container name) (Image name)
docker run -itd -p 5000:80 --name nodejs-v1  nodejs-app
