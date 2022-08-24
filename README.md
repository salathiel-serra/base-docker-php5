# base-docker-php5
Base repository for test project using php5.6

## Installation:
1. Clone the project:
```
https://github.com/salathiel-serra/base-docker-php5.git
```

2. Run in the project root via terminal:
```
docker-compose up -d
```

3. Wait a few moments and you will have:
```
Creating b-docker-app   ... done
Creating b-docker-nginx ... done
```

## Access

1. To access running application through browser:
```
http://localhost:8081/
```

2. To access the running container via terminal:
```
docker exec -it b-docker-app bash
```