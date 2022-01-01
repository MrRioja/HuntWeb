<h1 align="center">
Hunt Web
</h1>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=hunt&message=web&color=blueviolet&style=for-the-badge"/>
  <img src="https://img.shields.io/github/license/MrRioja/OmniStack-8?color=blueviolet&logo=License&style=for-the-badge"/>
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/MrRioja/HuntWeb?color=blueviolet&logo=TypeScript&logoColor=white&style=for-the-badge">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/MrRioja/HuntWeb?color=blueviolet&style=for-the-badge">
</p>

<p align="center">
  <a href="#sobre">Sobre</a> •
  <a href="#HuntWeb">HuntWeb</a> •
  <a href="#instalação">Instalação</a> •
  <a href="#tecnologias">Tecnologias</a> •
  <a href="#autor">Autor</a>  
</p>

<br><br><br>

## Sobre

<p align="justify">
 Projeto desenvolvido com o intuito de obter conhecimento básico no React.
 HuntWeb é uma aplicação feita em <strong>ReactJS</strong> para listagem de produtos. A aplicação consome uma <strong>API REST</strong> desenvolvida com <strong>NodeJS</strong>.</p>

#### :computer: Com este projeto coloquei em prática:

- [x] Componentização.
- [x] Estados do React.
- [x] Paginação.
- [x] Consumo de API's com o React.
- [x] Roteamento da aplicação.

<br>

## HuntWeb

O aplicativo HuntWeb consiste em uma aplicação para cadastro e listagem de produtos.
Esse repositório contém a versão web do projeto que possui duas telas, onde:

### Home:

É onde os produtos cadastrados no banco são exibidos. A tela é responsiva e possui botões de navegação que são habilitados com base na quantidades de produtos cadastrados.

<img src="./readme/Home.png" />

<br>
<img src="./readme/Home-Hover.png" />

<br>
<img src="./readme/Navigation.png" />

### Produto:

É onde os detalhes de um produto é exibido. A tela é aberta ao clicar no botão **Acessar** presente na listagem da tela **Home**

<img src="./readme/Product.png" />

## Instalação

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
Além disto é bom ter um editor para trabalhar com o código, como [VSCode](https://code.visualstudio.com/)

### 📱 Rodando o App

```bash
# Clone este repositório
$ git clone git@github.com:MrRioja/HuntWeb.git

# Acesse a pasta do projeto no terminal/cmd
$ cd HuntWeb

# Instale as dependências
$ npm install
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn

# Execute a aplicação
$ yarn start

# A aplicação será aberta no endereço http://localhost:3000/.
# Para que a listagem funcione é necessário que o backend esteja em execução.
```

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone git@github.com:MrRioja/Node-API.git

# Acesse a pasta do projeto no terminal/cmd
$ cd Node-API

# Instale as dependências
$ npm install
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ npm run dev
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn dev

# O servidor inciará na porta 3001 ou na porta definida no arquivo .env na variável APP_PORT - acesse <http://localhost:3001>
```

## Tecnologias

<img align="left" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/200px-React-icon.svg.png" alt="React Native" height="75" />

<br><br><br><br><br><br>

## Autor

<div align="center">
<img src="https://badges.pufler.dev/contributors/MrRioja/Omnistack-8?size=100&padding=5&bots=false"/>
<h1>Luiz Rioja</h1>
<strong>Backend Developer</strong>
<br/>
<br/>

<a href="https://linkedin.com/in/luizrioja" target="_blank">
<img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/mrrioja" target="_blank">
<img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:lulyrioja@gmail.com?subject=Fala%20Dev" target="_blank">
<img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://api.whatsapp.com/send?phone=5511933572652" target="_blank">
<img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>

<a href="https://join.skype.com/invite/tvBbOq03j5Uu" target="_blank">
<img alt="Skype" src="https://img.shields.io/badge/SKYPE-%2300AFF0.svg?style=for-the-badge&logo=Skype&logoColor=white"/>
</a>

<br/>
<br/>
</div>
