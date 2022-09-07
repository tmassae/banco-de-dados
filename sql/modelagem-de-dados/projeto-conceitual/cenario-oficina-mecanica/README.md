# Bootcamp Database Experience - DIO

## Desafio do projeto


### Objetivo:
Criar esquema conceitual para o contexto de oficina mecanica com base na narrativa fornecida.


### Narrativa:
* Sistema de controlee gerenciamentode execu��ode ordens de servi�o em uma oficina mec�nica
* Clientes levam ve�culos � oficina m�canica para serem consertadosou para passarem por revis�es peri�dicas
* Cada ve�culo � designado a uma equipe de mec�nicos que identifica os servi�os a serem executadose preencheuma OS com data de entrega.
* A partir da OS, calcula-se o valor de cada servi�o, consultando-se uma tabela de refer�ncia de m�o-de-obra 
* O valor de cada pe�a tamb�m ir� compora OS 
* O cliente autoriza a execu��odos servi�os 
* A mesma equipe avalia e executaos servi�os
* Os mec�nicos possuem c�digo, nome, endere�o e especialidade
* Cada OS possui: n�, data de emiss�o, um valor, status e uma data para conclus�odos trabalhos.
* Uma OS pode ser compostapor v�rios servi�os e um mesmo servi�o pode estarcontidoem mais de uma OS. 
* Uma OS pode ter v�rios tipos de pe�a e uma pe�a pode estar presenteem mais de uma OS


### Desenvolvimento:
MySQL Wokbench

### Arquivos:
* Oficina_Mecanica.mwb - vers�o final
* Diagrama_Oficina_Mecanica.png - Imagem do diagrama