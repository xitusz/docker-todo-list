# Docker Todo-List
[1/13] [Desenvolvimento Back-end](https://github.com/xitusz/Trybe/tree/main/03_Desenvolvimento-Back-end)

---

## Sumário

- [Contexto](#contexto)
- [Habilidades Desenvolvidas](#habilidades-desenvolvidas)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Clonando Repositório](#clonando-repositório)
- [Instalando Dependências](#instalando-dependências)
- [Executando Aplicação](#executando-aplicação)
- [Executando Testes](#executando-testes)

---

## Contexto

* Projeto desenvolvido para colocar em prática conhecimentos adquiridos em Docker / Docker Compose

---

## Habilidades Desenvolvidas

* Usar comandos dockers no CLI - Interface de linha de comando;
* Criar um contêiner Docker para uma aplicação de front-end;
* Criar um contêiner Docker para uma aplicação de back-end;
* Criar um contêiner Docker para uma aplicação de testes;
* Orquestrar os três contêineres utilizando o Docker compose.

---

## Tecnologias Utilizadas

* Docker
* Docker Compose

---

## Clonando Repositório:

* Clone o repositório
  ```sh
    git clone git@github.com:xitusz/docker-todo-list.git
  ```

---

## Instalando Dependências

* Entre na pasta do repositório que você clonou:
  ```sh
    cd docker-todo-list
  ```

* Instale as dependências
  ```sh
    npm install
  ```

* Entre na pasta da aplicação back-end:
  ```sh
    cd docker/todo-app/back-end
  ```

* Instale as dependências
  ```sh
    npm install
  ```

* Entre na pasta da aplicação front-end:
  ```sh
    cd ../front-end
  ```

* Instale as dependências
  ```sh
    npm install
  ```

---

## Executando Aplicação

* Aplicação desenvolvida pela [Trybe](https://www.betrybe.com/)

* Utilize o [Docker](https://www.docker.com/)

* Entre na pasta do repositório que você clonou:
  ```sh
    cd docker-todo-list/docker/
  ```

* Inicie o projeto:
  ```sh
    docker build -t todobackend ./todo-app/back-end/
  ```

  ```sh
    docker build -t todofrontend ./todo-app/front-end/
  ```

  ```sh
    docker build -t todotests ./todo-app/tests/
  ```

  ```sh
    docker-compose up --build -d
  ```

* Acesse o endereço em seu navegador:
  ```sh
    http://localhost:3000/
  ```

---

## Executando Testes

* Testes removidos pelo fato de terem sido criados pela [Trybe](https://www.betrybe.com/)

---
