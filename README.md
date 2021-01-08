# Sobre o projeto
Este projeto foi desenvolvido durante a **NLW #2 Next Level Week**, evento disponibilizado pela [**Rocketseat**](https://rocketseat.com.br/).

Proffy é uma plataforma de estudos online que ajuda pessoas a encontrarem professores online, de forma rápida e simples.

# Layout
No link abaixo você encontra o layout do projeto web.
* [Layout Proffy](https://www.figma.com/file/GHGS126t7WYjnPZdRKChJF/Proffy-Web?node-id=0%3A1)

# Como executar o projeto
## Pré-Requisitos
* [Node Js](https://nodejs.org/en/)
* [Git](https://git-scm.com/)
```bash
# Clone o repositório
$ git clone https://github.com/Lucas-Godoi/***verificar

# Acesse a pasta do projeto no prompt de comando
$ cd NLW-2 ***verficar

# Instale as dependências
$ npm install

# Execute o script "dev"
$ npm run dev

# O projeto se inciará na porta: 5500 - acesse http://localhost:5500
```

O projeto já está com alguns professores cadastrados, para obter a base de dados limpa basta:
```bash
#Deletar a base de dados, arquivo database.sqlite
$ rem -r src/database/database.sqlite

#Executar o arquivo db.js para a criação das tabelas
$ node src/database/db.js
```

## As seguintes ferramentas foram usadas na construção do projeto:

#### Front-end:
* HTML
* CSS
* JavaScript

#### Back-end (NodeJS)
* Express
* Nodemon
* Nunjucks

#### Database 
* Sqlite-Async

<h4 align=center>Por Lucas Godoi <a href="https://www.linkedin.com/in/godoi-lucas/">Entre em contato :)</a></a></h4>