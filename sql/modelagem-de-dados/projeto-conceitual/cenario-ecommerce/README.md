# Bootcamp Database Experience - DIO

## Desafio do projeto


### Objetivo:
Criar esquema conceitual para o contexto de e-commerce com base na narrativa fornecida.


### Narrativa:
* Os produtos s�o vendidos por uma �nica plataforma online. Contudo, estes podem ter vendedores distintos (terceiros) 
* Cada produto possui um fornecedor 
* Um ou mais produtos podem compor um pedido
* O cliente pode se cadastrar no site com seu CPF ou CNPJ 
* O Endere�o do cliente ir� determinar o valor do frete 
* Um cliente pode comprar mais de um pedido.
* Este tem um per�odo de car�ncia para devolu��o do produto
* O pedidos s�o criados por clientes e possuem informa��es de compra, endere�o e status da entrega
* Um produto ou mais compoem o pedido
* O pedido pode ser cancelado

### Refinando:
* Cliente PJ e PF � Uma conta podeser PJ ou PF, mas n�o pode ter as duas informa��es 
* Pagamento� Pode ter cadastradomais de uma forma de pagamento
* Entrega � Possui status e c�digo de rastreio 
 

### Desenvolvimento:
MySQL Wokbench

### Arquivos:
* Ecommerce_V1.mwb - vers�o inicial
* Ecommerce_V2.mwb - vers�o final com refinamentos do esquema
* Diagrama_Ecommerce.png - Imagem do diagrama 