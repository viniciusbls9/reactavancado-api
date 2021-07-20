# React Avançado - Won Games API

Esssa API está em desenvolvimento para o curso [React Avançado](https://reactavancado.com.br/)

## Ferramentas utilizadas

- [Strapi](https://strapi.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [graphql](https://graphql.org/)

## Requisitos

Esse projeto utiliza [PostgreSQL](https://www.postgresql.org/), então é necessário instalar na sua maquina local.
As configurações do banco de dados é encontrada no arquivo: [config/database](https://github.com/viniciusbls9/reactavancado-api/blob/master/config/database.js)

## Desenvolvimento

Após clonar o projeto, é preciso instalar as dependências do projeto:
```
yarn install
```

e rode o projeto utilizando:

```
yarn develop
```

Você pode acessar as seguintes URL's:
- `http://localhost:1337/admin` - dashboard Strapi
- `http://localhost:1337/graphql` - GraphQL Playground para testar as queries.