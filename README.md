# Dashboard de Vendas 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/roalbuquerque/projeto-sds3/blob/master/LICENSE) 

# Sobre o projeto

O Dashboard de Vendas é uma aplicação full stack web e mobile construída durante a 3ª edição da **Semana DevSuperior** (#sds3), evento organizado pela [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").

A aplicação consiste em uma apresentação de informações referente a vendas que são coletadas pelo backend feito em Spring boot, e depois são listados no app web feito em React, que também apresenta um dashboard com gráficos baseados nestes dados.

⚡ Observação: O projeto backend está hospedado no Hiroku, e como se trata da versão gratuita, ela adormece a aplicação caso não esteja em uso por 30 minutos.
Neste caso ao acessar o link abaixo, aguardar alguns segundos para que as informações carreguem. 😄

https://rafael-dsvendas.netlify.app/dashboard

## Layout mobile
![Mobile 0](https://github.com/roalbuquerque/projeto-sds3/blob/master/assets/Mobile00.jpg) ![Mobile 1](https://github.com/roalbuquerque/projeto-sds3/blob/master/assets/Mobile01.jpg) ![Mobile 2](https://github.com/roalbuquerque/projeto-sds3/blob/master/assets/Mobile02.jpg) 

## Layout web
![Web 0](https://github.com/roalbuquerque/projeto-sds3/blob/master/assets/web00.jpg)

![Web 1](https://github.com/roalbuquerque/projeto-sds3/blob/master/assets/web01.jpg)

![Web 2](https://github.com/roalbuquerque/projeto-sds3/blob/master/assets/web02.jpg)

## Modelo conceitual
![Modelo Conceitual](https://github.com/roalbuquerque/projeto-sds3/blob/master/assets/ModeloConceitual.png)

## Padrão de camadas
![Padrão de Camadas](https://github.com/roalbuquerque/projeto-sds3/blob/master/assets/padraoDeCamadas.png)

## Teste de requisição
![Teste de requisitção](https://github.com/roalbuquerque/projeto-sds3/blob/master/assets/postman.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- Apex Charts
## Ferramentas de Apoio
- Postman
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/roalbuquerque/projeto-sds3

# entrar na pasta do projeto back end
cd backend

# Abrir o projeto no "Spring Tool Suite 4"

# executar o projeto
Botão direito sobre a classe "DsvendasApplication.java" e >Run As>Spring Boot App

# o que acontece depois de executar o projeto backend
O banco será criado conforme scripts em data.sql

```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/roalbuquerque/projeto-sds3

# entrar na pasta do projeto front end web
cd frontend

# instalar dependências
yarn install
ou
npm install

# executar o projeto
yarn start
ou
npm start

# o que acontece depois de executar o ultimo comando:
A aplicação será aberta no navegador

```

# Autor

Rafael de Oliveira Albuquerque

📫 Você pode me encontrar aqui:
<p align="left">
  <a href="https://www.linkedin.com/in/rafaeloliveiraalbuquerque/" alt="Linkedin">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rafaeloliveiraalbuquerque/" /></a>

