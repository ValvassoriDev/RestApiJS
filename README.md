API REST - Node.js e Express
Este é um projeto simples desenvolvido com Node.js e Express, que simula uma API REST para gerenciamento de produtos em memória. Ele é ideal para quem está aprendendo os fundamentos de construção de APIs.

Esta API foi criada para facilitar o gerenciamento de produtos de forma simples e direta. Com ela, é possível listar todos os produtos cadastrados, buscar um produto específico pelo seu ID, adicionar novos itens, atualizar informações já existentes ou remover produtos da lista. Tudo funciona apenas com armazenamento em memória, ou seja, sem a necessidade de um banco de dados — ideal para testes, estudos ou protótipos rápidos.

Endpoints disponíveis
GET	/produtos - Lista todos os produtos
GET	/produtos/:id - Retorna um produto específico
POST	/produtos -	Adiciona um novo produto
PUT	/produtos/:id -	Atualiza um produto existente
DELETE	/produtos/:id -	Remove um produto
