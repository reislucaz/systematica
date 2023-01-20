<p align="center">
<img src="https://cdn.pixabay.com/photo/2020/07/08/17/05/gear-5384557_960_720.png" width="200" />
</p>

  <p align="center">Aplicação Full-stack Sistem-Ática</p>

## Description

Atenção, essa é uma versão em desenvolvimento, então pode apresentar bugs ou falhas inesperadas.

## Installation

### Crie o .env na pasta do servidor:
```bash
DATABASE_URL="... de acordo com configuração do Docker."
PORT="3001"
JWT_SECRET="secret"
JWT_EXPIRES_IN="1h"
REDIS_HOST="localhost"
REDIS_PORT="6380"
MODE="DEV"
```

### Após isso, digite no terminal na pasta raiz do projeto:
```
$ docker-compose up

após isso, entre no container do servidor e digite:

$ npx mikro-orm schema:fresh --seed --run
```


## Docs

A documentação pode ser acessada ao iniciar o servidor, ir para a rota /docs.

## Acompanhe:

- Author - [Lucas Reis](https://www.linkedin.com/in/lucasreis30/)
