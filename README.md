# DIO - Trilha .NET - Fundamentos
www.dio.me

## Desafio de projeto
Para este desafio, voc� precisar� usar seus conhecimentos adquiridos no m�dulo de fundamentos, da trilha .NET da DIO.

## Contexto
Voc� foi contratado para construir um sistema para um estacionamento, que ser� usado para gerenciar os ve�culos estacionados e realizar suas opera��es, como por exemplo adicionar um ve�culo, remover um ve�culo (e exibir o valor cobrado durante o per�odo) e listar os ve�culos.

## Proposta
Voc� precisar� construir uma classe chamada "Estacionamento", conforme o diagrama abaixo:
![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

A classe cont�m tr�s vari�veis, sendo:

**precoInicial**: Tipo decimal. � o pre�o cobrado para deixar seu ve�culo estacionado.

**precoPorHora**: Tipo decimal. � o pre�o por hora que o ve�culo permanecer estacionado.

**veiculos**: � uma lista de string, representando uma cole��o de ve�culos estacionados. Cont�m apenas a placa do ve�culo.

A classe cont�m tr�s m�todos, sendo:

**AdicionarVeiculo**: M�todo respons�vel por receber uma placa digitada pelo usu�rio e guardar na vari�vel **veiculos**.

**RemoverVeiculo**: M�todo respons�vel por verificar se um determinado ve�culo est� estacionado, e caso positivo, ir� pedir a quantidade de horas que ele permaneceu no estacionamento. Ap�s isso, realiza o seguinte c�lculo: **precoInicial** * **precoPorHora**, exibindo para o usu�rio.

**ListarVeiculos**: Lista todos os ve�culos presentes atualmente no estacionamento. Caso n�o haja nenhum, exibir a mensagem "N�o h� ve�culos estacionados".

Por �ltimo, dever� ser feito um menu interativo com as seguintes a��es implementadas:
1. Cadastrar ve�culo
2. Remover ve�culo
3. Listar ve�culos
4. Encerrar


## Solu��o
O c�digo est� pela metade, e voc� dever� dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no c�digo, em seguida, implemente conforme as regras acima.