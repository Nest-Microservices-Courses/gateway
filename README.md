<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Client Gateway Description
El gateway es el punto de comunicación entre nuestros clientes y nuestros servicios. Es el encargado de recibir las peticiones, enviarlas a los servicios corresponientes y devolver la respuesta al cliente.

## Installation
1. Clonar el repositorio.
2. Instalar las dependencias con el siguiente comando:
```bash
$ yarn install
```
3. Crear un archivo `.env` basado en el `env.template` que se encuentra en la raíz del proyecto.
4. Levantar los microservicios que se van a consumir.
5. Levantar el proyecto con uno de los siguientes comandos:
```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```
## Nats
```
docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
```

## Test

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```

