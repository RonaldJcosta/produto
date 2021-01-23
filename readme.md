The challenge

Your challenge is to develop an API, using Node.JS, for a product catalog management application. Thus, you must analyze and convert the user stories below into routes of an application.

User stories:

    As a user I would like to register a product so that I can have access to the data of this product in the future (Title, description, price, category)
    I as a user would like to be able to associate and edit a product category[x]
    As a user I would like to be able to access the list of all products[x]
    As a user I would like to be able to filter products by name or category[x]
    I as a user would like to be able to update the product data[x]
    I as a user would like to be able to delete a product from my catalog[x]


# Método de uso da api

 Para executar o projeto clone esse repositorio, inicie le usando nodemon app.js 
 use o inmsominia ou postman e use as rodas indicadas

 Criar uma categoria [post] http://localhost:3333/cadastro/categoria

Listar uma categoria [get] http://localhost:3333/cadastro/produtos 

Criar um produto [post] http://localhost:3333/cadastro/produtos (ao adicionar categoria coloque o id de uma categoria )

Listar os produtos [get] http://localhost:3333/produtos

Listar os produtos por categoria  [get] http://localhost:3333/produtos/search?categoria = "Id da categoria"
Listar os produtos por title  [get] http://localhost:3333/produtos/search?title = "name"

Editar a categoria de um produto [put] http://localhost:3333/produtos/categorias/<id do produto>

Editar um produto [put] http://localhost:3333/produtos/<id do produto>

Deletar um produto [put] http://localhost:3333/produtos/delete/<id do produto>

