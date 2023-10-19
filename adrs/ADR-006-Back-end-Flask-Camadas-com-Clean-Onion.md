
# ADR-006 - Back-end Flask - Camadas com Clean/Onion

## Title
Back-end Flask - Camadas com Clean/Onion.

## Status
Accepted

## Context
O Fintrackr tem a responsabilidade de gerenciar a lógica de negócios relacionada ao gerenciamento de finanças. A escolha da arquitetura do back-end é essencial para garantir que a aplicação seja flexível, testável e manutenível.

## Decision
Adotar uma combinação de arquitetura em camadas com Clean/Onion para o back-end do Fintrackr construído com Flask.

## Consequences
- **Separação de Responsabilidades**: Esta abordagem garante que as responsabilidades sejam claramente separadas em diferentes camadas.
- **Flexibilidade**: Facilita mudanças e evolução do código ao manter a lógica de negócios separada da infraestrutura.
- **Testabilidade**: Torna mais fácil escrever testes unitários para a lógica de negócios.
- **Manutenibilidade**: O código torna-se mais fácil de manter e entender.
- **Curva de Aprendizado**: Pode haver uma curva de aprendizado para desenvolvedores não familiarizados com a arquitetura Clean/Onion.
- **Complexidade**: A introdução de várias camadas e a separação rigorosa podem aumentar a complexidade inicial.
