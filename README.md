# Microsoft SQLServer con Docker

> Boilerplate de Docker-compose para disponer de una DB Sql Server 

![Microsft SQLServer](logo.png)

## Comandos

```sh
git init --initial-branch=master
git add .
git commit -am "Init project"
git remote add origin <url del repositorio>
git pull --rebase origin master
git push origin master
```

## Identificacion

| Dato     | Valor         |
| -------- | ------------- |
| hostname | localhost     |
| port     | 1433          |
| dbname   | master        |
| user     | sa            |
| pass     | definido por **MSSQL_SA_PASSWORD** en el archivo sapassword.env |

## Validar version docker-compose

```sh
docker-compose --version
```

## Acciones

### Levantar la imagen como servicio

```sh
docker-compose up -d
```

### Detener la imagen

```sh
docker-compose stop
```

### Borrar la imagen (y lo que conlleva)

```sh
docker-compose down
```

## Consultar archivo local

```sh
cd /usr/shared/ && ls && cat hello.txt | nl
```
