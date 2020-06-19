# Desafio01-RocketSeat
Desafio em Node.js usando os Requests Get, Post, Put e Delete e Middlewares


Imsomnia :



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
	"title":"pegar o cartão de crédito2"
}



# Alterar Título do projeto - Put:

http://localhost:3000/projects/0

Body:

{
	"title":"Fazer Compras 3"
}



# Deletar Projeto - Delete:

http://localhost:3000/projects/0
