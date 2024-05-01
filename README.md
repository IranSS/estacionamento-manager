# Sistema de Gerenciamento de Estacionamento

Este projeto foi desenvolvido como parte de um desafio proposto no módulo de fundamentos da trilha .NET da DIO (Digital Innovation One). O objetivo é criar um sistema simples de gerenciamento de estacionamento, capaz de adicionar veículos, remover veículos e listar os veículos presentes no estacionamento, além de calcular o valor cobrado pelo tempo de permanência.

## Contexto

Imagine que você foi contratado para desenvolver um sistema para um estacionamento, onde é necessário gerenciar os veículos estacionados e realizar operações básicas como adição, remoção e listagem de veículos.

## Proposta

O sistema consiste em uma classe chamada "Estacionamento" que possui três variáveis e três métodos:

### Variáveis

- `precoInicial`: Valor decimal representando o preço cobrado inicialmente para estacionar um veículo.
- `precoPorHora`: Valor decimal representando o preço cobrado por hora de estacionamento.
- `veiculos`: Lista de strings representando as placas dos veículos estacionados.

### Métodos

- `AdicionarVeiculo(placa)`: Método para adicionar um veículo ao estacionamento.
- `RemoverVeiculo(placa, horas)`: Método para remover um veículo do estacionamento e calcular o valor a ser cobrado.
- `ListarVeiculos()`: Método para listar todos os veículos presentes no estacionamento.

## Solução

O projeto consiste em um programa interativo que permite ao usuário realizar as seguintes ações:

1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

A solução implementa as funcionalidades descritas acima, seguindo as regras estabelecidas no desafio.

## Como Utilizar

Para utilizar o programa, basta seguir os seguintes passos:

1. Clone este repositório para o seu ambiente local.
2. Abra o projeto em um ambiente de desenvolvimento compatível com .NET.
3. Compile e execute o projeto.
4. Siga as instruções exibidas no console para interagir com o sistema de gerenciamento de estacionamento.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou reportar problemas encontrados.

## Desafio Original

O desafio original pode ser encontrado [aqui](https://github.com/digitalinnovationone/trilha-net-fundamentos-desafio).