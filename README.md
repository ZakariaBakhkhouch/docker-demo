## Guidance

Build the image.

```bash
docker build -t <image-name> -f DockerDemoApp/Dockerfile .
```

Run the image.

```bash
docker run --name <image-name> -e ASPNETCORE_ENVIRONMENT=Development -p 8080:8080 -p 8081:8081 <image-name>
```
