# NodejS-Docker-tutorial

## Build Image
`docker build -t nodejs-app .`

## Run the App (Container name) (Image name)
`docker run -itd -p 8080:8080 --name nodejs-v1  nodejs-app`
