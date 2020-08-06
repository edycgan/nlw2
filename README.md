# Visão Geral

Projeto desenvolvido durante a Next Level Week #2 da Rocketseat, ministrada pelo Diego Fernandes.

# Introdução

O aplicativo Proffy visa conectar professores e alunos por meio de uma interface simples e amigável. Cada professor pode indicar a matéria que deseja lecionar, os horários disponíveis, WhatsApp para contato e o preço da sua hora por aula. Os alunos conseguem procurar por professores, com base na matéria e horários que deseja, e entrar em contato diretamente com o professor.

# Execução

Para executar esta aplicação será necessário ter as seguintes ferramentas:

- Node.js
- Yarn

## Executando o Back-End

Para executar o Back-End, vá na pasta server e abra um terminal. Após, execute os seguintes comandos:
**yarn knex:migrate**
**yarn start**

## Executando o Front-End

Para executar o Front-End, vá na pasta web e crie um arquivo .env com a propriedade de nome "REACT_APP_API_URL" e como valor insira o endereço onde está localizado o seu Back-End.
Abra um terminal nesta mesma pasta e execute o seguinte comando:
**yarn start**
Pronto!

## Atualizando a versão

Ao baixar a versão mais recente, sempre vá na pasta server, abra um terminal e execute o seguinte comando:
**yarn knex:migrate**
