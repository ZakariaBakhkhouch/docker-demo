# build the image : 
docker build -t <image-name> -f DockerDemoApp/Dockerfile .

# run the image : 
docker run --name <image-name> -e ASPNETCORE_ENVIRONMENT=Development -p 8080:8080 -p 8081:8081 myapp
