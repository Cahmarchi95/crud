# Projeto Crud

Projeto para exercitar conceitos básicos em Angular


## 🛠️ Construído com

* [Angular 9](https://angular.io/docs)
* [Angular Material](https://material.angular.io/) 
* [Json-server](https://github.com/typicode/json-server) - simular um backend através de um arquivo db.json


# :hammer: Funcionalidades do projeto
- `Funcionalidade Cadastrar um produto`: Ao clicar no botão novo produto é exibido um formulário para cadastrar um novo produto, fazendo uma requisição do tipo POST para o backend no endpoint (http://localhost:4200/products/create)
- `Funcionalidade Editar um produto`: Ao clicar no ícone de lápis na tabela que exibe os produtos, é exibido um formulário para editar o produto selecionado, fazendo uma requisição do tipo PUT para o backend no endpoint (http://localhost:4200/products/update/:id)
- `Funcionalidade Excluir um produto`: Ao clicar no ícone de lixeira na tabela que exibe os produtos, é exibido um formulário com os dados do produto selecionado, para confirmar a exclusão, fazendo uma requisição do tipo DELETE para o backend no endpoint (http://localhost:4200/products/delete/:id)
- `Funcionalidade Exibir os produtos cadastrados` Ao navegar para produtos, será exibida uma tabela com o id, nome, preço e ações editar e excluir para cada produto, fazendo uma requisição do tipo GET para o backend no endpoint (http://localhost:4200/products)
