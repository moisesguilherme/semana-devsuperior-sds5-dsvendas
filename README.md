# DSVendas
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/moisesguilherme/semana-devsuperior-sds5-dsvendas/blob/main/LICENSE) 

# Sobre o projeto 

DSVendas é uma aplicação FullStack (Front-end web e Back-end com Java e Spring) construída durante a 5ª edição da **Semana DevSuperiror** (#sds5), evento organizado pela escola de programação [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um Dashboard de vendas, com gráficos exibindo a taxa de sucesso de vendas por vendedor. Uma lista paginada com um relatório das vendas e um outro gráfico destacando o resultado total das vendas.

[Link do projeto em produção no Netlify](https://devsuperior-sds5-dsvendas.netlify.app/)

## Layout web
![Web 1](https://github.com/moisesguilherme/assets/blob/main/sds5-dsvendas/front-web-01.png) 

![Web 2](https://github.com/moisesguilherme/assets/blob/main/sds5-dsvendas/front-web-02.png)

![Web 3](https://github.com/moisesguilherme/assets/blob/main/sds5-dsvendas/front-web-03.png)


# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/moisesguilherme/semana-devsuperior-sds5-dsvendas.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor
Moisés Guilherme

https://www.linkedin.com/in/moises-guilherme/
