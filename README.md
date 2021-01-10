# DS Delivery

# Sobre o projeto

https://epitacio-sds2.netlify.app/

DS Delivery é uma aplicação full stack web construída durante a 2ª edição da **Semana DevSuperior** (#sds2), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um programa para serviço delivery para restaurante, onde o usuário escolhe os produtos pelo catálogo disponibilizado, fornece o endereço de entrega, e depois estes dados são armazenados no banco em estados de 'pendente' e 'entregue'.

## Layout web
![Web 1](https://github.com/epitacioneto/assets/blob/main/HOME%20DELIVERY.png)

![Web 2](https://github.com/epitacioneto/assets/blob/main/SELECIONAR%20PRODUTOS.png)

## Modelo conceitual
![Modelo Conceitual](https://github.com/devsuperior/sds2/blob/master/assets/modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/epitacioneto/dsdeliver-sds2

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/epitacioneto/dsdeliver-sds2

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
npm install

# executar o projeto
npm start
```

# Autor

Epitácio Pessoa de Brito Neto

https://www.linkedin.com/in/epitacio-neto-61ba98168/