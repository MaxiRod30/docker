## Crear imagen
```
docker build -t apache:php .
```

## Ver contenedores activos
```
docker ps
```

## Ejecutar contenedor
```
docker run -d -p 8080:80 apache:php
```

## Borrar contenedor activo
```
docker rm -fv 208d097d3a56
208d097d3a56 = CONTENEDOR_ID
```
## Borrar imagen
```
docker rmi 208d097d3a56
208d097d3a56 = ID IMAGEN
```
## Crear nueva imagen a partir de nombre distinto de Dockerfile
```
docker build -t test -f my-dockerfile .
```