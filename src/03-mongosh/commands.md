
## Asi nos conectamos al servicio que esta corriendo en docker
## docker compose exec _nombreservicio_ bash
```sh
docker-compose exec mongodb bash
```

## Nos conectamos con mongosh
```sh
mongosh ""
```

## Comandos que podemos ejecutar
```sh
show dbs
show collections
```

```sh
use("platzi_store");
db.products.find();
```