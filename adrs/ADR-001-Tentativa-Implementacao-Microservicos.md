# ADR-001 - Tentativa de Implementar Todo o Projeto do Fintrackr Usando Microserviços

## Title

Tentativa de Implementar Todo o Projeto do Fintrackr Usando Microserviços.

## Status

Rejected

## Context

O projeto Fintrackr visa oferecer uma ferramenta robusta para o gerenciamento de finanças. Com o aumento da complexidade e a variedade de funcionalidades, considerou-se a possibilidade de utilizar uma abordagem totalmente baseada em microserviços.

## Decision

Tentar implementar todo o projeto do Fintrackr usando uma arquitetura baseada em microserviços.

## Consequences

- **Especialização**: Cada microserviço pode ser otimizado para sua função específica.
- **Flexibilidade**: Microserviços podem ser desenvolvidos, escalados ou modificados independentemente.
- **Resiliência**: Falhas em um microserviço não afetariam outros microserviços.
- **Complexidade Aumentada**: A gestão de múltiplos microserviços pode complicar o desenvolvimento e a manutenção.
- **Overhead de Comunicação**: A comunicação entre microserviços pode introduzir latências.
- **Rejeitado**: Devido ao tempo e à complexidade aumentada, decidiu-se não seguir essa abordagem.
