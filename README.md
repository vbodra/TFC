# Projeto Trybe Futebol Clube ⚽️

Projeto realizado por [Vinicius Bodra](https://www.linkedin.com/in/vinicius-bodra/) e [Trybe](https://www.betrybe.com/).

---

## Sumário

- [O que é a aplicação](#O-que-é-a-aplicação)
- [A aplicação deve ser capaz de](#A-aplicação-deve-ser-capaz-de)
    - [Sem fazer login ou logado como pessoa usuária](#Sem-fazer-login-ou-logado-como-pessoa-usuária)
    - [Fazendo login como pessoa administradora](#Fazendo-login-como-pessoa-administradora)
- [O que foi desenvolvido](#O-que-foi-desenvolvido)
    - [Por mim](#Por-mim)
    - [Pela Trybe](#Pela-Trybe)
- [Tecnologias](#tecnologias)
- [Como acessar a aplicação](#Como-acessar-a-aplicação)


---

## O que é a aplicação

Um site que simula uma tabela de classificação de um campeonato de futebol.

<br/>

**Como pessoa usuária não cadastrada ou logada com uma conta de pessoa usuária não-administradora** é possível visualizar e filtrar a tabela de classificação (de acordo com as classificações geral, de times mandantes e de times visitantes), visualizar e filtrar a tabela de partidas (de acordo com o status da partida - em andamento ou finalizada) e efetuar login e logout.

<br/>

**Como pessoa usuária administradora** é possível visualizar e filtrar a tabela de classificação (de acordo com as classificações geral, de times mandantes e de times visitantes), visualizar e filtrar a tabela de partidas (de acordo com o status da partida - em andamento ou finalizada), editar e finalizar partidas em andamento, adicionar novas partidas e efetuar login e logout.

<br/>

***Todas as adições e alterações de partidas alteram a tabela de classificação na rota '/leaderboard'.*** **Adicione uma goleada do seu time favorito contra um time rival e veja a mudança na classificação!**

---

## A aplicação deve ser capaz de

- ##### Sem fazer login ou logado como pessoa usuária
    - Acessar a tabela de classificação na rota '/leaderboard';
        - Filtrar a tabela de classificação a partir de diferentes cenários ('geral', 'como mandante' e 'como visitante');
    - Acessar a tabela de partidas na rota '/matches';
        - Filtrar a tabela de partidas a partir do status ('todos', 'em andamento' e 'finalizada');
    - Realizar login na rota '/login':
        - Para fazer login como pessoa usuária use as seguintes credenciais (sem as aspas):
            - login: 'user@user.com';
            - senha: 'secret_user';

- ##### Fazendo login como pessoa administradora
    - Todas as ações de uma pessoa usuária comum (com execeção, é claro, de fazer login como pessoa usuária);
    - Realizar login na rota '/login':
        - Para fazer login como pessoa administradora use as seguintes credenciais (sem as aspas):
            - login: 'admin@admin.com';
            - senha: 'secret_admin';
    - Alterar partidas que ainda estejam em andamento a partir da rota '/matches';
    - Finalizar partidas em andamento a partir da rota '/matches/settings';
    - Adicionar novas partidas a partir da rota '/matches';

---

## O que foi desenvolvido

- ### Por mim
    - Configuração do banco de dados a partir de ORM;
    - Arquitetura MSC;
    - API REST com TypeScript;
    - Alerta no frontend sobre a autoria do projeto;
    - Deploy do Backend no Heroku;
    - Deploy do Frontend no GitHub Pages;

- ### Pela Trybe
    - **Frontend;**

---

## Tecnologias

- Docker;
- Heroku;
- MySQL;
- Sequelize ORM;
- NodeJS;
- TypeScript;
- Express;
- JWT;

---

## Como acessar a aplicação

Basta acessar esse [link](https://vbodra.github.io/TFC-Frontend).
