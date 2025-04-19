# Modelagem_Banco_de_Dados

## Banco de Dados E-commerce

A **modelagem de banco de dados** é o processo de criar uma estrutura lógica e organizada para armazenar, gerenciar e acessar os dados de forma eficiente.

É como desenhar o " esqueleto" do banco de dados **antes de construí-lo de fato,** definindo :
- Quais tabelas vão existir;
- Quais são os campos (colunas) de cada tabela;
- Como essas tabelas vão se relacionar entre si;
- Que tipo de dado cada campo pode armazenar 
- Quais são as chaves primárias e estrangeiras;

Usando o MYSql Workbench.

__Foco:__

Venda de Produtos

__Levantamento de Requisitos__

Produto:

- Vendidos por unica plataforma Online
- Podem ter vendedores distintos(terceiros)
- Cada produto possui um fornecedor
- Um ou mais produto podem compor o pedido

Cliente:

- O cliente devem cadastrar no site com CPF ou CNPJ
- Deve ser informado o endereço para calcular o frete
- Um cliente comprar mais de um pedido
- Este tem um periodo de carência para devolução do produto

Pedido:

- Pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
- Um produto ou mais compoem o pedido
- O pedido pode ser cancelado






