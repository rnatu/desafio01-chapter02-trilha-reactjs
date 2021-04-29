<h1 align="center">
<img alig src="./public/logo.svg" width=500 alt="Desafio RocketShoes">
  <br>
  <br>
    Chapter 2 - Desafio Principal
</h1>

<h4 align="center">
  Criando um hook de carrinho de compras
</h4>

<p align="center">
  <a href="https://www.linkedin.com/in/rafael-martins92/">
    <img alt="Made By" src="https://img.shields.io/static/v1?label=Made%20By&message=Renato%20Xavier&color=6C4FBB&style=for-the-badge">
  </a>

  <img alt="Languages" src="https://img.shields.io/github/languages/count/rnatu/ignite-desafio-criando-um-hook-de-carrinho-de-compras?style=for-the-badge">

  <img alt="Top Language" src="https://img.shields.io/github/languages/top/rnatu/ignite-desafio-criando-um-hook-de-carrinho-de-compras?style=for-the-badge">
</p>

<p align="center">
Nesse desafio, criei uma aplicação para treinar o que aprendi até agora no ReactJS
</p>

<p align="center">
  <a href="#-sobre">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-resultado">Resultado</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias-utilizadas">Tecnologias utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-utilizar">Como utilizar</a>
</p>

## 📜 Sobre o projeto

Nesta aplicação o meu principal objetivo foi criar um hook de carrinho de compras. Tive acesso a duas páginas, um componente e um hook para implementar as funcionalidades pedidas nesse desafio:

- Adicionar um novo produto ao carrinho;
- Remover um produto do carrinho;
- Alterar a quantidade de um produto no carrinho;
- Cálculo dos preços sub-total e total do carrinho;
- Validação de estoque;
- Exibição de mensagens de erro;
- Entre outros.

Este Desafio visa o aprendizado com ReactJS e TypeScript.

## 📷 Resultado

![Rocketshoes](./public/rocketshoes.gif)

## 🚀 Tecnologias utilizadas

- [ReactJS](https://pt-br.reactjs.org/)
  - [styled-components](https://styled-components.com/)
  - [toastify](https://fkhadra.github.io/react-toastify/introduction)
- [TypeScript](https://www.typescriptlang.org/)
- Fake API
  - [JSON Server](https://github.com/typicode/json-server)
- [axios](https://github.com/axios/axios)
- [localStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

## ℹ️ Como utilizar

### Instalando Dependências

```bash
    # Instalar as dependências
    $ yarn
```

### Iniciando Fake Api - JSON Server

```bash
    # Iniciando "servidor" JSON Server
    $ yarn server

    # O servidor estará sendo executado na porta:3333 - Basta acessar: 
    # http://localhost:3333/stock e/ou http://localhost:3333/products
  
```

### Iniciando aplicação

```bash
    # Iniciando "servidor" JSON Server
    $ yarn start

    # A aplicação será aberta na porta:3000 - Basta acessar: http://localhost:3000 
```

<h4 align="center">
    Made with 💜 by Renato Xavier
</h4>
