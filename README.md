# React Native - Proffy

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/osvaldokalvaitir/react-native-proffy/blob/master/LICENSE)
![](https://img.shields.io/github/package-json/v/osvaldokalvaitir/react-native-proffy.svg)
![](https://img.shields.io/github/last-commit/osvaldokalvaitir/react-native-proffy.svg?color=red)
![](https://img.shields.io/github/languages/top/osvaldokalvaitir/react-native-proffy.svg?color=yellow)
![](https://img.shields.io/github/languages/count/osvaldokalvaitir/react-native-proffy.svg?color=lightgrey)
![](https://img.shields.io/github/languages/code-size/osvaldokalvaitir/react-native-proffy.svg)
![](https://img.shields.io/github/repo-size/osvaldokalvaitir/react-native-proffy.svg?color=blueviolet)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)

Aplicação Proffy usando React Native, Expo, TypeScript, @react-navigation/native, @react-navigation/stack, @react-navigation/bottom-tabs, React Native Async Storage e expo-font consumindo os recursos da API do [Node.js - Proffy](https://github.com/osvaldokalvaitir/nodejs-proffy).

## Índice

- [Capturas de Tela](#capturas-de-tela)

  - [Home](#home)

  - [Estudar - Filtros](#estudar---filtros)
  
  - [Estudar - Disponíveis](#estudar---disponíveis)
  
  - [Estudar - Favoritos](#estudar---favoritos)

  - [Dar aulas](#dar-aulas)

- [Desenvolvimento](#desenvolvimento)

  - [Configuração do Ambiente](#configuração-do-ambiente)

  - [Instalação do Projeto](#instalação-do-projeto)

  - [Execução do Projeto](#execução-do-projeto)

- [Utilizados no Projeto](#utilizados-no-projeto)

  - [Bibliotecas](#bibliotecas)

  - [APIs](#apis)

## Capturas de Tela

### Home

![Home](/.github/assets/home.png)
Esta é a primeira tela, que é a apresentação do projeto, podendo escolher entre estudar e dar aulas, exibe também o total de conexões realizadas.

### Estudar - Filtros

![Study - Filters](/.github/assets/study-filters.png)
Nesta tela, é necessário escolher os filtros para exibir os professores disponíveis.

### Estudar - Disponíveis

![Study - Available](/.github/assets/study-available.png)
Nesta tela, é exibido todos os professores disponíveis de acordo com o filtro escolhido, podendo salvar o professor nos favoritos ou entrar em contato.

### Estudar - Favoritos

![Study - Favorites](/.github/assets/study-favorites.png)
Nesta tela, exibe todos os professores que foram salvos como favoritos, ficando gravados no banco de dados Async Storage do smartphone.

### Dar aulas

![Teach](/.github/assets/teach.png)
Nesta tela, é exibida uma mensagem indicando que o professor que deseja dar aulas precisa se cadastrar pela plataforma web.

## Desenvolvimento

### Configuração do Ambiente

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/README.md) e siga `Configuração de Ambiente`.

### Instalação do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga `Instalação de Projeto`.

### Execução do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/expo-cli.md) e siga `Execução de Projeto para Desenvolvimento no React Native no Emulador Android e iOS`.

## Utilizados no Projeto

### Bibliotecas

- [@react-navigation/bottom-tabs](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@react-navigation-bottom-tabs.md)

- [@react-navigation/native](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@react-navigation-native.md)

- [@react-navigation/stack](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@react-navigation-stack.md)

- [@expo-google-fonts/archivo](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@expo-google-fonts-archivo.md)

- [@expo-google-fonts/poppins](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@expo-google-fonts-poppins.md)

- [Axios](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/axios.md)

- [Expo CLI](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/expo-cli.md)

- [expo-font](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/expo-font.md)

- [React Native Async Storage](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@react-native-community-async-storage.md)

- [React Native Gesture Handler](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-gesture-handler.md)

- [React Native MaskedView](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@react-native-community-masked-view.md)

- [react-native-reanimated](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-reanimated.md)

- [react-native-safe-area-context](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-safe-area-context.md)

- [react-native-screens](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-screens.md)

- [TypeScript](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/typescript.md)

### APIs

- **[Node.js - Proffy](https://github.com/osvaldokalvaitir/nodejs-proffy)**

  - **Rotas**

    - Classes

      - Lista classes

    - Conexões

      - Exibe total de conexões
      - Cria conexões
