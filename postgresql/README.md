

## configuracion 🚀

La base de datos configurada con:
```
USER=lirium
PASSWORD=Lirium123
DATABASE=ninio_mensajero
PORT=5432
```

### Instalación 🔧

Ingrese a la carpeta ninio_mensajero
```
cd ninio_mensajero
```
descargamos las imagenes
```
docker pull postgres
```

levantamos el el orquestador docker-compose
```
docker-compose up -d
```


detenemos docker-compose
```
docke-compose down
```

ingresamos a la base de datos
```
psql -U lirium -h localhost -d ninio_mensajero
```

