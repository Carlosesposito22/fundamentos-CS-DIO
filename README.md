# Sistema de Gerenciamento de Estacionamento 🚗

Este projeto é uma solução desenvolvida como parte do desafio da trilha .NET da DIO, com foco nos fundamentos da linguagem C#. Ele simula um sistema básico de gerenciamento de estacionamento, permitindo o controle de veículos, cálculo de valores e listagem dos carros estacionados.

---

## Funcionalidades

O sistema de estacionamento oferece as seguintes funcionalidades principais:

* **Adicionar Veículo**: Permite registrar a placa de um veículo que está entrando no estacionamento, adicionando-o à lista de veículos estacionados.
* **Remover Veículo**: Possibilita remover um veículo do estacionamento. Ao remover, o sistema solicita o tempo de permanência em horas e calcula o valor total a ser pago, com base em um preço inicial e um preço por hora.
* **Listar Veículos**: Exibe todos os veículos atualmente estacionados. Caso não haja nenhum veículo, uma mensagem informativa é mostrada.

---

## Estrutura do Projeto

O projeto é construído em torno de uma classe central chamada `Estacionamento`, que encapsula a lógica de negócio do sistema.

---

## Como Usar

O sistema interage com o usuário através de um menu de opções no console:

1.  **Cadastrar veículo**: Adiciona um novo veículo ao estacionamento.
2.  **Remover veículo**: Retira um veículo do estacionamento e calcula o valor a ser pago.
3.  **Listar veículos**: Exibe a lista de todos os veículos estacionados.
4.  **Encerrar**: Finaliza a execução do programa.

Basta executar o programa e seguir as instruções apresentadas no menu.
