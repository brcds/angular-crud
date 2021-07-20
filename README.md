# Desenvolvendo um CRUD utilizando Angular 9.

## Backend json-server

Cria um arquivo **package.json**, onde fica/podemos colocar as dep do projeto.
> npm init -y 


Instala o **json-serve**, que vai ser a api da aplicação, necessario criar um file com o nome **db.json**, o 'json-server' basicamente ler um arquivo json e cria uma api baseada nesse **json**.
> npm i json-server 




No arquivo **package.json** criar o comando para iniciar a api **json-server**,  **--watch** monitora o arquivo db.json na porta 3001;

>  "scripts": {
>    "start": "json-server --watch db.json --port 3001"  
>  }

Inicia a api;
> npm start 


# frontend Conceitos Angular-9

**Conceitos**

<p align="center">
    <img width="" height="" src="/readme-assets/angular.png">
    <img width="" height="" src="/readme-assets/cli_angular.png">
    <img width="" height="" src="/readme-assets/ts_angular.png">
    <img width="" height="" src="/readme-assets/arvore_componentes_angular.png">
</p>

** Conceitos Essenciais **

Inicialização.
_main.ts_ -> _AppModule_ -> _AppComponent_ 

**Componentes**
_html_ -> home.component.css 
_CSS_  -> home.component.html
_TS_   -> home.component.ts

Como referencia um component (encapsula as 3 tecnologias dentro do component.)
> <app-home></app-home>


