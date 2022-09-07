# Bootcamp Database Experience - DIO

## Desafio do projeto


### Objetivo:
Criar esquema conceitual para o contexto de oficina mecanica com base na narrativa fornecida.


### Narrativa:
* Sistema de controlee gerenciamentode execuçãode ordens de serviço em uma oficina mecânica
* Clientes levam veículos à oficina mêcanica para serem consertadosou para passarem por revisões periódicas
* Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executadose preencheuma OS com data de entrega.
* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra 
* O valor de cada peça também irá compora OS 
* O cliente autoriza a execuçãodos serviços 
* A mesma equipe avalia e executaos serviços
* Os mecânicos possuem código, nome, endereço e especialidade
* Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusãodos trabalhos.
* Uma OS pode ser compostapor vários serviços e um mesmo serviço pode estarcontidoem mais de uma OS. 
* Uma OS pode ter vários tipos de peça e uma peça pode estar presenteem mais de uma OS


### Desenvolvimento:
MySQL Wokbench

### Arquivos:
* Oficina_Mecanica.mwb - versão final
* Diagrama_Oficina_Mecanica.png - Imagem do diagrama