<h1 align="center">NLW Heat - Node.js</h1>

<div align="center">
    <img alt="DoWhile logo" src="./src/assets/logo.svg" width="250px"/>
</div>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>
</p>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/pablwoAraujo/node_heat">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/pablwoAraujo/node_heat">
  
  <a href="https://github.com/pablwoAraujo/node_heat/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/pablwoAraujo/node_heat">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">

  <img src="https://img.shields.io/static/v1?label=NLW&message=Heat&color=8257E5&labelColor=000000" alt="NLW Heat" />
</p>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)

## 🚀 Como executar

> Obs.: Nesse projeto temos autenticação via OAuth com o GitHub

- Clone o repositório e acesse a pasta;
- Faça uma copia do arquivo `.env.example` para `.env` e preencha com as suas credenciais do GitHub;
- Instale as dependências com `yarn`;
- Executa as migrations com `yarn prisma migrate dev`;
- Inicie o servidor com `yarn dev`;

A aplicação pode ser acessada em [`localhost:4000`](http://localhost:4000).

<br/>
<div align="center">
  <img alt="nlw heat" src="./src/assets/nlwheat.png" width="150px" />
</div>


> Projeto desenvolvido na missão Impulse do [NLW Heat](https://nextlevelweek.com/)