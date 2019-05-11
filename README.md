# Node.js REST API boilerplate

<<<<<<< HEAD
## Installation requirements

Before cloning API repository, make sure that you have:

 - Installed [Node.js](https://nodejs.org/en/download/) v10.6.0 or greater
 - Installed [Yarn](https://yarnpkg.com/en/docs/install#windows-stable) v1.15.2 or greater

For production environment (hosting using IIS on Windows):
- Installed [IISNode](https://github.com/tjanczuk/iisnode)
- Installed [URLRewrite](https://www.iis.net/downloads/microsoft/url-rewrite)

## Installation

After clonning the repository, run these commands below:

### Dev Environment

- Install all depedencies
```
yarn
```

### Production Environment

running on server

- Install production depedencies
```
yarn install --prod
```

## Project Commands

- Run the API locally (ex: localhost:port/route)
```
yarn dev
```

- Build project and generate the /dist folder to publish on the server
```
yarn build
```

- Run unit/integration tests
```
yarn test
```
=======
## Prerequisites
Nodejs
Yarn

## Getting Started
clone the project

run yarn on vscode terminal no install libs

## Commands
yarn run -> start the project in localhost

yarn test -> run tests

yarn build -> generate ./Dist folder to production enviroment

### VsCode Eslint Config
"eslint.autoFixOnSave": true, //ESLINT gera fix automatico em regras quebradas
"eslint.validate": [
    "javascript",
    "javascriptreact",
    {"language": "typescript", "autoFix": true},
    {"language": "typescriptreact", "autoFix": true}        
]
>>>>>>> 44b5e52c858d66ba91e37dcbd7f51f5c15e037ec
