# RedisDemo

Simple demo on redis caching for .NET web apps (Blazor)

## Steps:
1. run redis server `docker run -d --name redis-server -p 6379:6379 redis`
2. (Optional) open interactive terminal on redis container `docker exec -it redis-server sh`
3. (Optional) try redis cli `redis-cli `, `SET mykey "hello redis"`, `GET mykey`

Reference: https://www.youtube.com/watch?v=UrQWii_kfIE&ab_channel=IAmTimCorey
