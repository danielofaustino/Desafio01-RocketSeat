# Desafio01-RocketSeat
Desafio em Node.js usando os Requests Get, Post, Put e Delete e Middlewares

- Node.js
- Express.js
- Nodemon





# Imsomnia:

# Mostrar Projetos - GET:

http://localhost:3000/projects



# Criar um projeto - Post:

http://localhost:3000/projects

Body: 

{
	"id":0,
	"title":"Crud Nodejs",
	"tasks":[""]
}



# Criar Tarefa - Post:

http://localhost:3000/projects/0/tasks

Body:

{
	"title":"Middlewares"
}



# Alterar Título do projeto - Put:

http://localhost:3000/projects/0

Body:

{
	"title":"Método Get"
}



# Deletar Projeto - Delete:

http://localhost:3000/projects/0
