# docker-develop-environment
Compose files for setting up different services as environment for developing microservices.

## Local Docker Registry

```
cd registry/
mkdir data
docker-compose up -d
```

See a list of pushed images: [localhost:5000/v2/_catalog](http://localhost:5000/v2/_catalog)
