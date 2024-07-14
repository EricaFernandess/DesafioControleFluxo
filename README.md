# DesafioControleFluxo - DIO

## Descrição

O projeto `DesafioControleFluxo` é um programa Java que recebe dois números inteiros como parâmetros via terminal. O programa calcula a quantidade de interações necessárias para imprimir os números incrementados a partir do primeiro parâmetro até o segundo. Se o primeiro parâmetro for maior que o segundo, o programa lançará uma exceção customizada chamada `ParametrosInvalidosException`.

## Estrutura do Projeto

O projeto contém as seguintes classes:

1. **ParametrosInvalidosException**: Uma exceção customizada para tratar o caso em que o primeiro parâmetro é maior que o segundo.
2. **Contador**: A classe principal que contém a lógica do programa.

## Como Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/DesafioControleFluxo.git

2. **Compile as classes**:
   ```bash
   javac Contador.java ParametrosInvalidosException.java
   
3. **Execute o programa**:
   ```bash
   java Contador
   
