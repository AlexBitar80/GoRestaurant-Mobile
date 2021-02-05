<h3 align="center">
	BootCamp Gostack - Desafio 11 - GoRestaurant Mobile
</h3>

</div>
<p align="center">
  Nesse desafio foi construido um pequeno app mobile o GoRestaurant onde deveriamos listar os pratos de comidas da Fake API, navegar para a página com detalhes do prato e aumentar ou diminiur a quantidade de pratos de comidas.
</p>

<br/>

<p align="center">
  <img alt="GitHub watchers" src="https://img.shields.io/github/watchers/AlexBitar80/GoRestaurant-Mobile?style=social">

  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/AlexBitar80/GoRestaurant-Mobile">

  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/AlexBitar80/GoRestaurant-Mobile?style=social">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/AlexBitar80/GoRestaurant-Mobile">

  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/AlexBitar80/GoRestaurant-Mobile">
</p>

<br/>

## :star: Tecnologias usadas neste projeto

O projeto está utilizando as seguintes tecnologias:

-  [typescript](https://www.typescriptlang.org/)
-  [react-native](https://reactnative.dev/)
-  [jest](https://jestjs.io/)
-  [react-native-vector-icons](https://www.npmjs.com/package/react-native-vector-icons)
-  [axios](https://www.npmjs.com/package/axios)
-  [json-server](https://www.npmjs.com/package/json-server)
-  [styled-components](https://styled-components.com/)
-  [react-navigation](https://reactnavigation.org/)

## :rocket: Como rodar
Para clonar e rodar esse projeto você vai precisar do [Node](https://nodejs.org/en/) do [Yarn](https://yarnpkg.com/) ou do [Npm](https://www.npmjs.com/get-npm) e do [Git](https://git-scm.com/) instalado na rua máquina.

```bash
# Faça o clone deste repositório para qualquer pasta de sua preferencia
$ git clone https://github.com/AlexBitar80/GoRestaurant-Mobile AppGoRestaurant

# Vá até essa pasta
$ cd AppGoRestaurant

# rode esses comandos para instalar as dependências
$ yarn || npm install

# O projeto está utilizando uma fake API e para executar utilize:
$ yarn json-server server.json -p 3333

# use esses comandos para rodar o P
$ yarn start || npm run start

# use esses comandos para rodar o Projeto no seu emulador do android
$ yarn android || npm run android

# use esses comandos caso esteja utilizando o emulador do iOS
$ yarn ios || npm run ios

# use esses comandos para rodar os testes
$ yarn test || npm run test
```

por padrão assim que o comando para rodar no emulador for iniciado ele ira abrir uma segundo aba do terminal com o Metro Bundler que serve para ficar monitorando e atualizando o app mobile, mas pode haver casos onde ele por padrão não irá abrir essa segunda aba, nesses casos basta rodar esses comandos abaixo

```bash
$ yarn start || npm run start

# e executar esses comandos novamente se for Android
$ yarn android || npm run android

# ou IOS
$ yarn ios || npm run ios
```
