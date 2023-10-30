# Banco-de-dados---I

O desenvolvimento de um projeto de banco de dados passa por fases importantes para a sua implementação, como a de projeto conceitual. Diante disso, crie uma entidade que tenha atributos simples, composto e multivalorado.

Entidade: Produto

Atributos:

Código (simples): representa o código único do produto.
Nome (simples): representa o nome do produto.
Descrição (simples): representa uma breve descrição do produto.
Preço (simples): representa o preço do produto.
Categoria (composto): representa a categoria do produto, composto pelos seguintes atributos:
Nome (simples): representa o nome da categoria.
Segmento (simples): representa o segmento ao qual a categoria pertence.
Fornecedores (multivalorado): representa os fornecedores do produto, podendo ter mais de um fornecedor, cada um com os seguintes atributos:
Nome (simples): representa o nome do fornecedor.
Telefone (simples): representa o telefone do fornecedor.
Email (simples): representa o email do fornecedor.
Essa entidade representa um produto que possui um código, nome, descrição, preço, categoria (composta por nome e segmento) e pode ter múltiplos fornecedores (cada um com nome, telefone e email).
