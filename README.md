<h1 align="center">
  <img alt="logo-gobarber" src="https://cybersaturn-hackathon.github.io/cybersaturn/src/assets/logo.png" width="500px">
</h1>

<h3 align="center">
  SaturnSports Homepage
</h3>

<p align="center">Use o site que nem o Tony Stark!</p>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/CyberSaturn-Hackathon/homepage?color=darkblue">

  <a href="http://github.com/iamthepoe" target="_blank" rel="noopener noreferrer">
    <img alt="Made by" src="https://img.shields.io/badge/made%20by-CyberSaturn-darkblue">
  </a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/CyberSaturn-Hackathon/homepage?color=darkblue">

  <a href="https://github.com/PeruibeTEC/Server/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/CyberSaturn-Hackathon/homepage?color=darkblue">
  </a>
</p>

## 📋 Índice

- [Geral](#geral)
- [Tecnologias](#tecnologias)
- [Iniciando o projeto](#iniciando-o-projeto)
  - [Requisitos](#requisitos)
  - [Instalando e configurando o projeto](#instalando-e-configurando-o-projeto)
- [Como usar](#-como-usar)

## 👀 Geral

SaturnSports é uma aplicação desenvolvida durante o hackathon da Etec de Peruíbe em 2023 com o objetivo de facilitar o gerenciamento e consumo dos jogos escolares.
Este repositório contém somente uma parte da aplicação, a que diz respeito a interação do usuário com o site interativo usando TensorFlow.
Toda as referências para a criação deste material foram retiradas das aulas do professor <a href="https://www.linkedin.com/in/erickwendel/" target="_blank">Erick Wendel</a>, um dos maiores nomes do Node.js no Brasil!

## 🚀 Tecnologias

As principais tecnologias utilizadas foram:

- [Node.js](https://nodejs.org/en/)
- [TensorFlow](https://www.tensorflow.org/?hl=pt-br)
- [FingerPose](https://github.com/andypotato/fingerpose)

## 💻 Iniciando o Projeto

### Requisitos

- [Node.js](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/) ou [Yarn](https://classic.yarnpkg.com/)
- Uma câmera.

### Instalando e configurando o projeto

*Clone o repositório e acesse sua pasta*

```bash
$ git clone https://github.com/CyberSaturn-Hackathon/homepage && cd homepage
```

*Siga os passos*

```bash
# Instale as dependências
$ npm install

# Inicie o servidor
$ npm run start

# Voalá, servidor rodando! =)
```

## 🤔 Como usar

1 - Primeiramente, abra o site localmente (ou caso prefira, acesse o deploy para entrar no site sem baixar nada https://cybersaturn-hackathon.github.io/homepage/pages/home/) e o acesse com o navegador de sua preferência. Recomendamos o Microsoft Edge.
<br>
2 - O site pedirá permissão para acessar sua câmera. Aceite para que o TensorFlow se inicie.
<br>
3 - Navegue no site usando os gestos de mão. Observação: faça isso num ambiente com iluminação decente, caso contrário, seus gestos podem serem detectados corretamente.
<br>

Lista de gestos:

<h3>✊️</h3> (Mão fechada) - Scroll para baixo.
<br>
<h3>🖐</h3> (Mão aberta) - Scroll para cima.
<br>
<h3>🤏</h3> (Pinça) - Clique.
