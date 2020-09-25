# Docker-compose-wordpress
The docker compose YML file runs wordpress, phpmyadmin and mariadb in localhost

## Tools
```
- Docker
- Docker-compose
```

## Images
- wordpress
- mariadb
- phpmyadmin

## Services
- db
- wordpress
- phpmyadmin

### wordpress url
```
localhost:8000
```

### phpmyadmin url
```
localhost:8181
```
## Run the services
```
- docker-compose up -d
```

#### Note
 **phpmyadmin** and **wordpress** services depend on **db** service
 
 ## References
- [Phpmyadmin docker image](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)
- [wordpress docker image](https://hub.docker.com/_/wordpress)
 
