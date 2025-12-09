# Trabalho Final - Qualidade e Teste de Software (Tema 3)

## Integrantes
* Lucas Neves

## Sobre o Projeto
Este projeto implementa uma API REST para cálculos de notas escolares (Tema 3), utilizando Java e Spring Boot. O sistema permite calcular médias, encontrar maior e menor nota através de endpoints HTTP.

## Tecnologias Utilizadas
* Java 17/21
* Spring Boot (Web)
* JUnit 5 (Testes Unitários)
* JMeter (Testes de Carga)

## Como Rodar
1. Clone o repositório.
2. Execute a classe `QualidadeApplication.java`.
3. A API estará disponível na porta 8081.

## Documentação da API (Endpoints)

### 1. Média Aritmética
* URL: `/api/notas/media`
* Método: GET
* Entrada: Lista de notas (ex: `notas=10,8,6`)
* Saída: Média calculada (ex: `8.0`)

### 2. Média Ponderada
* URL: `/api/notas/ponderada`
* Método: GET
* Entrada: Lista de notas e lista de pesos (ex: `notas=10,5&pesos=2,3`)
* Saída Média ponderada

### 3. Maior Nota
* URL: `/api/notas/maior`
* Método: GET
* Entrada: Lista de notas
* Saída: A maior nota da lista

### 4. Menor Nota
* URL: `/api/notas/menor`
* Método: GET
* Entrada: Lista de notas
* Saída: A menor nota da lista