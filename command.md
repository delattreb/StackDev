# Commandes

## Prérequis

Créer les répertoires:
> ->binding ->binding/redis_data  ->binding/mariadb_data  

## Redis

Utiliser redis-cli:
```sh
docker exec -it redis redis-cli
```

```sh
127.0.0.1:6379> SET hello world
OK
127.0.0.1:6379> GET hello 
"world"
```

