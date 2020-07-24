####  Bootcamp - GoStack 11
# 🚀 Nível 01 - Mobile com React Native

## Sobre

- Este projeto em React Native irá consumir os dados da API listada abaixo
  - [Nível 01 - Back-end com Node.js](https://github.com/fabiosvf/bootcamp-gostack-11-nivel-01-back-end-com-node-js)

---

## Roteiro

- Nesta seção será descrito o roteiro com todos os passos para criação do projeto em React Native com a utilização do comando "react-native init"

### Criando o projeto
- Preparar o ambiente para executar aplicações React Native
  - [Passo a Passo para Preparar o Ambiente React Native](https://react-native.rocketseat.dev/)
- Abrir o terminal
- Acessar o local onde será criado o projeto
- Criar o projeto inicial em React Native com a configuração padrão
```
$ react-native init NOME_PROJETO
```
  - Esse comando cria o projeto dentro de uma pasta com o mesmo nome do projeto
- Acessar a pasta do projeto
```
$ cd NOME_PROJETO
```
- Abrir a pasta do projeto no Visual Studio Code
```
$ code .
```

### Customizando o ambiente inicial
- Excluir os arquivos ".eslintrc.js" e ".prettierrc.js"

### Executando a aplicação pela primeira vez
- Executar a aplicação em um Emulador Android
```
$ react-native run-android
```

### Instalando bibliotecas e editando configurações
- Instalar a biblioteca 'axios'
  - Essa biblioteca é responsável por fazer as chamadas API para conectar o nosso ambiente Mobile com o Back-end
```
$ yarn add axios
```

---

## Tecnologias utilizadas

#### Dependências de Projeto
- [axios](https://yarnpkg.com/package/axios)
- [react](https://yarnpkg.com/package/react)
- [react-native](https://yarnpkg.com/package/react-native)

#### Dependências de Desenvolvimento
- [@babel/core](https://yarnpkg.com/package/@babel/core)
- [@babel/runtime](https://yarnpkg.com/package/@babel/runtime)
- [@react-native-community/eslint-config](https://yarnpkg.com/package/@react-native-community/eslint-config)
- [babel-jest](https://yarnpkg.com/package/babel-jest)
- [eslint](https://yarnpkg.com/package/eslint)
- [jest](https://yarnpkg.com/package/jest)
- [metro-react-native-babel-preset](https://yarnpkg.com/package/metro-react-native-babel-preset)
- [react-test-renderer](https://yarnpkg.com/package/react-test-renderer)

---

## Como executar
- Prepare o ambiente React Native
  - [Passo a Passo para Preparar o Ambiente React Native](https://react-native.rocketseat.dev/)
- Crie uma pasta para o projeto
- Acesse a pasta
- Faça o clone do projeto
```
$ git clone https://github.com/fabiosvf/bootcamp-gostack-11-nivel-01-mobile-com-react-native.git .
```
- Atualize as bibliotecas
```
$ yarn
```
- Inicie o emulador android
```
$ react-native run-android
ou
$ yarn android
```