# Simulador de Cartão de Crédito

Desafio prático para consolidar conceitos de **POO** em Java: classes, objetos, construtores, encapsulamento, listas e ordenação.

## 🎯 Objetivo do Projeto

Criar um programa de console que simule o uso de um **cartão de crédito**, permitindo:

- Definir um limite inicial
- Registrar várias compras
- Verificar se há limite disponível para cada compra
- Mostrar relatório final com saldo restante e lista de compras ordenada por valor

## Requisitos do Desafio

- Criar classe `Compra` com atributos: descrição e valor
- Criar classe `CartaoCredito` com:
  - limite
  - saldo (ou valor disponível)
  - lista de compras realizadas
  - método para registrar compra (retorna boolean indicando sucesso)
- No `main`:
  1. Perguntar o limite do cartão
  2. Criar o cartão
  3. Loop de registro de compras:
     - Perguntar descrição e valor
     - Tentar registrar
     - Informar se a compra foi realizada ou não
     - Perguntar se deseja continuar
  4. Ao finalizar: mostrar
     - Saldo final
     - Lista de todas as compras **ordenadas por valor** (crescente)

### Observações importantes

- Uso de apenas `Scanner` para entrada de dados
- Usar **construtores** para inicializar os objetos
- Tratar entradas inválidas de forma simples (valores negativos, não-números, etc.)
- A lista de compras deve ser ordenada **pelo valor** na exibição final


