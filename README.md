## init

```zsh
docker-compose run -d kong-db

docker-compose run kong kong migrations bootstrap

docker-compose down
```

## start
```zsh
docker-compose up -d
```

## konga
```zsh
open http://localhost:1337
```


