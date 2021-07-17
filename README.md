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

## frontend 
