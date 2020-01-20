# omnistack10-mobile DevRadar
Semana Omnistack 10.0 da Rockatseat

## :rocket: Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)

## 💻 Projeto

O DevRadar é um projeto que visa conectar Dev que trabalham com as mesmas tecnologias e estão em localidades proximas.

## Como testar o projeto?

<strong>Primeiramente acessar o [repositorio do back-end](https://github.com/luanperosa/omnistack10-backend) e seguir as instruções para executar a API.</strong>

<strong>O proximo passo é acessar o [repositorio do front-end](https://github.com/luanperosa/omnistack10-web) e também seguir as instruçes para rodar a aplicação.</strong>

O projeto mobile foi desenvolvido com o <strong>Expo</strong>, siga os passos para rodar a aplicação no seu celular mas fique a vontade para acessar a documentaço do [Expo](https://expo.io) e verificar outras formas de testar o app mobile pelo emulador por exemplo. 

Depois do clone desse repositorio executar o comando `npm i` para instalar as dependencias e executar o comando `npm start`, irá abrir a interface do Expo, acessar a pasta raiz da aplicação, /src/services/api.js e na <strong>baseURL</strong> incluir o endereço IP que aparece na <strong>interface do Expo</strong> com excessão da porta. Realizar o mesmo procedimento na pasta src/pages/List.js incluindo o mesmo endereço IP no <strong>socketio</strong>. Vide o .gif abaixo para entender melhor todo o processo. 

## Link da API

https://github.com/luanperosa/omnistack10-backend


## Link do projeto Web

https://github.com/luanperosa/omnistack10-web