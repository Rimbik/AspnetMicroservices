https://hub.docker.com/_/redis
docker pull redis
docker run -d -p 6379:6379 --name aspnetrun-redis redis

See Logs:
docker logs -f aspnetrun-redis

run redis image:
docker exec -it aspnetrun-redis /bin/bash


Try Redis command >>
redis-cli
ping - PONG

set key value
get key
set name mehmet
get name
