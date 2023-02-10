# Resilia Individual Módulo 3

## Contexto
Para esse projeto deveriamos criar um servidor do tipo Json-Server com 2 ou mais rotas, nas quais o usuário podera realizar o CRUD (CREATE, READ, UPDATE, DELETE), por meio do, POST(criar um novo elemento na rota), GET(ver um elemento da rota), PUT(atualizar um elemento da rota), DELETE(deletar um elemento da rota).


## Como Usar
Ápos fazer o git clone do repositório na sua máquina e abrir o projeto usando VSCode ou o editor de código da sua preferência, você irá notar que o projeto já conta com o node-modules, o json e o arquivo de JavaScript criando a inicialização do json-server.
<br>
1º Abrir o terminal e colococar o comando:
<br>
$ npm install json-server --save-dev
<br>2º Rodar o json-watch para acessar o localhost:
<br>
$ npx json-server --watch db.json
<br> Com isso aparecera no terminal o link do Localhost
<br>3º Utilizar uma ferramenta para testar a API:
<br>
Para esse passo recomendamos o uso o insomnia. Com essa ferramenta você podera testar o servidor, com o CRUD.

## Exemplos

GET
Caso você queira apenas visualizar 1 elemento da rota, você deve acrescentar uma / com o id desejado no final da URL.
![image](https://user-images.githubusercontent.com/118377204/218102849-91507c85-8ed6-4b0c-a15d-5194508bef28.png)

<br>
POST
Nessa rota, você precisa escrever os dados que deseja que sejam inseridos.

![image](https://user-images.githubusercontent.com/118377204/218103344-0a276613-716d-4143-b36b-bd30177aeca2.png)

<br>
PUT
Nessa rota, você precisa escrever os dados que deseja que sejam alterados.

![image](https://user-images.githubusercontent.com/118377204/218103798-ad3943c4-e5f5-404a-b1d7-ce5db41cd15a.png)

<br>
DELETE
Caso você queira apenas deletar 1 elemento da rota, você deve acrescentar uma / com o id desejado no final da URL.

![image](https://user-images.githubusercontent.com/118377204/218104402-dc45c5db-fac7-420a-addd-6e9235d2ab78.png)

# Tecnologias Utilizadas

 ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
 ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
 ![image](https://user-images.githubusercontent.com/116887504/218183177-0dd59c6b-3898-41f1-99e1-23e448052ccf.png)





