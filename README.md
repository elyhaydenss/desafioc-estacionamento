# Sistema de Estacionamento

Este projeto implementa um sistema simples de gerenciamento de estacionamento, permitindo adicionar, remover e listar veículos estacionados. O sistema calcula o custo do estacionamento com base em um preço inicial e um preço por hora.

## Descrição

A classe `Estacionamento` é responsável por gerenciar os veículos e calcular os valores cobrados com base no tempo em que o veículo permaneceu no estacionamento.

### Funcionalidades

1. **Adicionar Veículo**: Permite ao usuário adicionar a placa de um veículo à lista de veículos estacionados.

2. **Remover Veículo**: Remove um veículo da lista de estacionados, calculando o valor total a ser pago com base na quantidade de horas que o veículo permaneceu no estacionamento.

3. **Listar Veículos**: Exibe todas as placas dos veículos atualmente estacionados.

### Estrutura da Classe

- **Atributos:**
  - `precoInicial`: Valor cobrado inicialmente ao estacionar.
  - `precoPorHora`: Valor cobrado por cada hora de estacionamento.
  - `veiculos`: Lista que armazena as placas dos veículos estacionados.

- **Construtor:**
  - `Estacionamento(decimal precoInicial, decimal precoPorHora)`: Inicializa o estacionamento com os valores fornecidos para o preço inicial e o preço por hora.

- **Métodos:**
  - `AdicionarVeiculo()`: Solicita ao usuário a placa do veículo e a adiciona à lista.
  - `RemoverVeiculo()`: Solicita a placa do veículo e a quantidade de horas estacionadas, calcula o valor total e remove o veículo da lista.
  - `ListarVeiculos()`: Exibe a lista de veículos estacionados.

### Requisitos

- .NET 8.0 ou superior

### Considerações

- Ao remover um veículo, o sistema solicita a quantidade de horas que o veículo permaneceu no estacionamento para calcular o valor total.
