# EColeta (NLW #1)

O Ecoleta é um webapp que tem por objetivo fazer a conexão entre empresas/entidades que coletam resíduos orgânicos ou inorgânicos com pessoas que precisam descartar esse tipo de resíduos.

## Content

```
backend (nodeJS)
frontend (reactJS)
mobile (react native)
```

Backend node desenvolvido utilizando Knex como query builder, banco de dados SQLite3.

### Run backend

1 - dependências:

npm install

2 - scripts do Knex para migrates e seeds:

npm run knex:migrate
npm run knex:seed

3 - script para iniciar a API:

npm run start

acesse o endereço: `http://localhost:3333'