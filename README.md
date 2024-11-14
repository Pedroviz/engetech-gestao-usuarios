# Engetech Gestão de Usuários

Uma aplicação web para gerenciar usuários desenvolvida para a Engetech Soluções Ltda.

## Descrição

Este projeto é uma aplicação de gestão de usuários que permite a criação, edição, exclusão e visualização de usuários registrados. O sistema inclui autenticação com token JWT, uma interface para administração de usuários e conformidade com a LGPD, utilizando uma checkbox de consentimento no registro.

## Tecnologias Utilizadas

- **Frontend**: React.js, Axios
- **Backend**: Node.js, Express, MongoDB
- **Autenticação**: JSON Web Tokens (JWT)

## Funcionalidades

- **Landing Page**: Página inicial de apresentação do sistema.
- **Autenticação**: Página de login para usuários.
- **Cadastro de Usuários**: Página para novos usuários se registrarem.
- **Gestão Administrativa**: Página de administração para visualizar, editar e excluir usuários.
- **Logout**: Botão para o usuário sair do sistema.

## Pré-requisitos

- Node.js e npm instalados
- MongoDB em execução localmente ou através de um serviço online

## Instalação

1. Clone este repositório:
   
   git clone https://github.com/usuario/engetech-gestao-usuarios.git
   cd engetech-gestao-usuarios

2. Instale as dependências do backend:

   cd backend
   npm install

3. Inicie o servidor backend:

   node src/index.js

4. Em uma nova janela do terminal, instale as dependências do frontend:


   cd ../frontend
   npm install

5. Inicie o servidor frontend:

   npm start

6. Acesse a aplicação:

Frontend: http://localhost:3000
Backend: http://localhost:5000
