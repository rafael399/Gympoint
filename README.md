## :question: Informação

Este projeto se refere ao backend da aplicação Gympoint que foi desenvolvida durante o Bootcamp GoStack da [RocketSeat](https://https://rocketseat.com.br/) e é a primeira parte do desafio final.
O repositório original do projeto pode ser encontrado [aqui](https://github.com/rafael399/RocketSeat/tree/master/Gympoint)

## :computer: Instalação e execução

1. Faça um clone desse repositório;
2. Entre na pasta rodando `cd Gympoint`;
3. Rode `yarn` para instalar as dependências;
4. Crie um banco de dados no `postgres` com o nome de `gympoint`;
5. Renomeie o arquivo `.env.example` para `.env`;
6. Coloque as suas credenciais dentro do `.env`;
7. Rode `yarn sequelize db:migrate` para executar as migrations;
8. Rode `yarn sequelize db:seed:all` para executar a seed;
9. Rode `yarn dev` para iniciar o servidor.
10. Rode `yarn queue` para iniciar as filas. (opcional)
