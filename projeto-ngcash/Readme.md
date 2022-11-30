<h1 align="center">
   ---  BACKEND EM NODE E FRONTEND EM REACT ---
</h1>



## 💻 Sobre o Projeto

Criação de uma aplicação fullstack, com uso do Docker com objetivo de possibilitar que usuários cadastrados na plataforma NG consigam 
realizar transferências internas entre si. Utilizei para isso uma API do pix que gera uma chave aleatória onde o usuário em sua dashboard,
insira o valor que quer transferir sem pontos ou vírgulas, e ao clicar no botão automáticamente gera um código que deve ser colado, 
pelo usuário que quer enviar o pagamento. Utilizei uma imagem pública de um banco de dados da DIO, que se assemelha bastante ao objetivo do projeto.

## 💡 Informações de como executar o projeto

```bash

  # Clonar todo o repositório ou em partes "backend-app" e "frontend-app"

  # Acessar a pasta do projeto

  # Estando na pasta com os dois projetos, abrir três consoles um para acessar a pasta frontend-app, 
  # outro para acessar a pasta backend-app, e o terceiro para acessar a pasta backend-app porém para 
  # monitorar a execução do contêiner Docker ao executar o comando (docker-compose up). 
  
  # Ambas as pastas, rodar o comando -> yarn 

  # Backend-app, Rodar o comando para subir a base de dados para o seu docker -> docker-compose up 

  # Backend-app, Rodar o comando -> npm run dev ou yarn dev

  # Frontend-app, Rodar o comando -> npm start ou yarn start

```

## 🛠 Tecnologias

Ferramentas usadas no projeto:

- [React.js][react]
- [Styled-Components][styled]
- [Node.js][nodejs]
- [Express][express]
- [TypeScript][typescript]
- [Docker][docker]  
- [TypeOrm][typeorm]
- [JsonWebToken][jsonwebtoken]
- [Nodemon][nodemon]
- [Crypto-JS][cryptojs]
- [express-async-erros][expresserrors]
- [Vscode][vscode]

Feito por Felipe Joseph 👋🏽 [Contato!](https://www.linkedin.com/in/felipe-almeida-04/)

