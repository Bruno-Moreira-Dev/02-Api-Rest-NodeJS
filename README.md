# Requisitos Funcionais

- [ ] O usuário deve poder criar uma nova transação;
- [ ] O usuário deve poder obter um resumo da sua conta;
- [ ] O usuário deve poder listar todas as transações que já ocorreram;
- [ ] O usuário deve poder visualizar uma transação única;

# Regra de Negócio

- [ ] A transação pode ser do tipo crédito que somará ao valor total ou débito que subtrairá;
- [ ] Deve ser possível identificarmos o usuário entre as requisições;
- [ ] O usuário só pode visualizar transações o qual ele criou;

# Inicializando o projeto

Para rodar as migrations:

- Para versões recentes:
npm run knex -- migrate:latest

Para versões de node 18 para baixo:
- npm run knex-deprecated -- migrate:latest

Feito isto, rodar `npm install` e `npm run dev` para iniciar o projeto.