# Be The Hero

![logo][logo_img]

---
:rocket: **OmniStack Week 11.0**

![plataforms][bethehero_plataform]

# :rocket: Tecnologias utilizadas
Nesse projeto foram utilizadas as seguintes tecnologias:

* NodeJS
* ReactJS
* React Native
* [Expo](https://expo.io/)
* [Knex.js](http://knexjs.org)
* SQLite

# :computer: Projeto
O projeto consiste em desenvolver um ambiente tecnológico para conectar ONGs com voluntário (Heroes) comovidos a ajudar.  

Pelo aplicativo web, construido com ReactJS, as ONGs podem cadastrar as suas informações de contato e os casos sob os seus cuidados.  

O aplicativo mobile, construido com React Native e Expo, a comunidade pode visualizar todos os casos cadastrados e, conforme sua preferência, entrar em contato com a ONG e realizar sua doação.  

O backend, construido em NodeJS, recebe e disponibiliza todas essas informações persistindo elas em um banco de dados SQLite, utilizando o Knex para construir as consultas.

# :electric_plug: Como instalar

Os passos a seguir são pré-requisitos para os três ambientes.

* Navegue a te a pasta do projeto
* Execute o comando a seguir para instalar as dependências do projeto  
```
$ npm install
```

## Backend

```bach
# Criar banco de dados
$ knex migrate:latest

# Executar aplicação
$ npm run dev

# ou

$ npm run start
```

## Frontend

```bach
# Executar aplicação
$ npm run start
```

## Mobile

```bach
# Executar aplicação
$ npm run start
```

# Proximos passos

* [ ] Introduzir teste automatizados
* [ ] Segurança com JWT


[logo_img]: /blob/logo.svg
[bethehero_plataform]: /blob/bethehero.jpeg