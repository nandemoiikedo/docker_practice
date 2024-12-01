```
docker image build --no-cache -t go/echo:latest
docker container run -d -p 9000:8080 go/echo:latest
curl http://localhost:9000
```
