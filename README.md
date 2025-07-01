# express-mongo
Node.js: criando uma API Rest com Express e MongoDB

# Comandos q foram usados
01. Foi instalado um projeto node, irá criar um arquivo: package.json:
- npm init -y

02. Foi instalado o nodemon que detecta alterações automaticamente antes de exibir:
 - npm install nodemon@3.0.1

 - e no scripts do package.json foi criado o "dev" 
 "scripts": {
  "dev": "nodemon server.js",
  "test": "echo \"Error: no test specified\" && exit 1"
}

- A aplicação roda ao digitar no terminal: npm run dev

03. Foi instalado o framework Express na versão 4.18.1 e implementado os metodos: CRUD
- npm install express@4.18.1

04. Foi criado uma conta no mongodb para usar o mongo como banco de dados NoSql e um cluster e um database chamado 'livraria (livros)' e instalado uma biblioteca chamada Mongoose que faz a conexão entre o app e o mongo:
- npm install mongoose@7.3.4

05. 