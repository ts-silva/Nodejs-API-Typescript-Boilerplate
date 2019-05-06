# Nodejs-API-Typescript-Boilerplate
A boliterplate with Nodejs, express, eslint, typescrypt and tests

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
