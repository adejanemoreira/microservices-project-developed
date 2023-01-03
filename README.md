## microservices-project-developed
![image](https://user-images.githubusercontent.com/93550467/210370853-eba21bd8-f478-4465-9fd9-67f013279546.png)

### Projeto de microsserviços
Defina seu e-mail e senha para enviar o e-mail de matrícula do usuário através do microsserviço acadêmico.
Você vai precisar configurar uma conta do gmail para realizar esse envio. Para isso, defina no docker-compose.yml as variáveis GMAIL_USER e GMAIL_PASSWORD com os valores corretos.
Para que seu e-mail e senha funcionem, você deve OU desativar autenticação em 2 fatores OU utilizar uma senha de app, conforme é explicado nesse [tópico do Google](https://support.google.com/accounts/answer/185833?hl=pt-BR).


## Description

Para clonar repositório e iniciar os submodulos $ git clone --recursive https://github.com/adejanemoreira/microservices-project-developed

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
