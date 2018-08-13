# com.mycompany.docker.redis
Redis

To build and run

1. docker build -t mycompany.redis .
2. docker run -p 6379:6379 --name mycompany.redis mycompany.redis

# com.mycompany.docker.redis
Redis

Available as Docker image "a142857/mycompany.redis" on https://hub.docker.com

To build and run

1. docker build -t mycompany.redis .
2. docker run -p 6379:6379 --name mycompany.redis mycompany.redis

To build and push

1. docker build -t mycompany.redis .
2. docker tag mycompany.redis a142857/mycompany.redis
3. docker push a142857/mycompany.redis

"--name mycompany.redis" is used as a redis host name within mycompany.tomcat base container for
