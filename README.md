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

## Installation

#### Clone the repository
```
- git clone git@github.com:Njaya2019/docker-compose-wordpress.git
```
#### Change the directory to the project's root directory
```
- cd docker-compose-wordpress
```

#### Download and install docker desktop

```
- Install docker desktop
```

##### Run the services in the docker compose file
```
- docker-compose up -d
```
### wordpress url
```
localhost:8000
```

### phpmyadmin url
```
localhost:8181
```

#### Note
 **phpmyadmin** and **wordpress** services depend on **db** service
 
 ## References
- [Phpmyadmin docker image](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)
- [wordpress docker image](https://hub.docker.com/_/wordpress)
 
