# redis-server
docker file for running a redis server in local

 docker build -t local-redis .
 docker run --name local-redis-container -it -p6379:6379 local-redis
