
# ConectaDados

> ConectaDados é uma aplicação web de lista de tarefas (to-do list) desenvolvida em React, utilizando autenticação e banco de dados do Firebase. O objetivo é permitir que usuários criem uma conta, façam login e gerenciem suas tarefas de forma simples e segura.

## Funcionalidades

- Cadastro de novos usuários com e-mail e senha
- Login de usuários autenticados
- Logout seguro
- Criação de tarefas associadas ao usuário logado
- Interface responsiva e intuitiva

## Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [Firebase Authentication](https://firebase.google.com/docs/auth)
- [Firebase Firestore](https://firebase.google.com/docs/firestore)
- [React Router DOM](https://reactrouter.com/)

## Estrutura do Projeto
```├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── App.js
│   ├── firebaseConnection.js
│   ├── index.css
│   ├── index.js
│   ├── pages/
│   │   ├── Admin/
│   │   │   ├── admin.css
│   │   │   └── index.js
│   │   ├── Home/
│   │   │   ├── home.css
│   │   │   └── index.js
│   │   └── Register/
│   │       └── index.js
│   └── routes/
│       ├── index.js
│       └── Private.js
├── package.json
└── README.md
````

## Como rodar o projeto

1. **Clone o repositório:**

   ```sh
   git clone https://github.com/diatsilva007/ConectaDados.git
   ```

   1.1 **Entre na pasta do projeto:**

   ```sh
   cd ConectaDados
   ```

2. **Instale as dependências:**

   ```sh
   npm install
   ```

3. **Configure o Firebase:**

   - Renomeie o arquivo `src/firebaseConnection.js.example` para `src/firebaseConnection.js` (caso exista).
   - Insira suas credenciais do Firebase no arquivo `src/firebaseConnection.js`.

4. **Inicie o projeto:**

   ```sh
   npm start
   ```

   O app estará disponível em [http://localhost:3000](http://localhost:3000).

## Scripts Disponíveis

- `npm start` — Inicia o servidor de desenvolvimento.
- `npm run build` — Gera uma versão de produção na pasta `build`.
- `npm test` — Executa os testes.
- `npm run eject` — Remove a configuração padrão do Create React App.

## Estrutura das Páginas

- **Home:** Tela de login do usuário.
- **Register:** Tela de cadastro de novo usuário.
- **Admin:** Tela principal para gerenciamento das tarefas (acesso restrito a usuários autenticados).

## Observações

- O arquivo firebaseConnection.js está listado no .gitignore para evitar o versionamento de credenciais sensíveis.
- Para utilizar o Firebase, crie um projeto em [https://console.firebase.google.com/](https://console.firebase.google.com/) e configure a autenticação por e-mail/senha e o Firestore.

## Licença

Este projeto está sob a licença MIT.

---

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

<div align="center">
  
# Feito com 💙
| [<img src="https://avatars.githubusercontent.com/u/143373573?v=4" width="100" height="100"><br><sub>Diogo Ataide</sub>](https://github.com/diatsilva007)
| :---: |

 <p><img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/></p>
 
 # 🙅‍♂️
 
 </div>
