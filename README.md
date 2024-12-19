# Json-server
Criando um servidor de testes com json-server

## Iniciar o projeto no diretório escolhido

	npm init -y

## Instalar o Json-Server

 Após a criação do package.json Insalar o Json-server

	npm i json-server

O json server ler um arquivo e cria uma api baseada neste arquivo

- Crie o arquivo no projeto com o nome **db.json**

## No arquivo gerado, criaremos um objeto com os endpoints da api

	{
	
	    "products": [
	
	        {
	
	        "id" : 1,
	
	        "name" : "Caneta Bic Preta",
	
	        "price" : 5.89
	
	        },
	
	        {
	
	        "id" : 2,
	
	        "name" : "Lápis 2B",
	
	        "price" : 1.89
	
	        },
	
	        {
	
	        "id" : 3,
	
	        "name" : "Caderno 100 folhas",
	
	        "price" : 15.89
	
	        },
	
	        {
	
	        "id" : 4,
	
	        "name" : "Borracha",
	
	        "price" : 0.89
	
	        },
	
	        {
	
	        "id" : 5,
	
	        "name" : "Apontador",
	
	        "price" : 1.89
	
	        }
	
	    ]
	
	}

## Criar no package. json um script para iniciar meu servidor.

	"scripts": {
	
	    "start": "json-server --watch db.json --port 3001"
	
	  },

## Inicie com npm start

	 npm start