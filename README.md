# minio

## Initialize
```shell script
cp -n .env.dist .env
```

## Run
```shell script
docker-compose -f docker-compose.yml up -d
```

## Run with nginx proxy
```shell script
docker-compose -f docker-compose.yml -f docker-compose.nginx-proxy.yml up -d
```