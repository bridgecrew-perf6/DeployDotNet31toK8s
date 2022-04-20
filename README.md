```
docker build -t docker-webapi-demo31 -f WebAPI/Dockerfile .

docker run -d --name docker-webapi-demo31 -p 9003:80 -e ASPNETCORE_ENVIRONMENT=Development docker-webapi-demo31
```

# TEST
```
curl http://localhost:9003/weatherforecast
```