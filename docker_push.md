# Docker commands
My docker/k8s doc

```
docker login
docker container ls
docker commit -a "Wu Qifu" -m "for Keycloak, SprintBoot demo" 0ed09aedcd0c wuqifu/keycloak
docker push wuqifu/keycloak

docker run -d -p 8080:8080 wuqifu/keycloak
```

https://hub.docker.com/r/wuqifu/keycloak/
