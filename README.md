# Simple project for pipeline tests

This project is beeing used by Jenkins running on Kubernetes for .Net Core Docker deployment.

## Build and Run steps

```bash
docker build -t helloworld .
docker run -d -p 5000:80 helloworld
```