
# ADR-007 - Microserviço com Pandas - Hexagonal

## Title

Microserviço com Pandas - Hexagonal.

## Status

Accepted

## Context

O Fintrackr tem uma necessidade específica de processar dados de planilhas para integração com o sistema. Esta funcionalidade é distinta das funções principais da aplicação e pode necessitar de escalabilidade e adaptabilidade independentes.

## Decision

Adotar a arquitetura hexagonal para o microserviço especializado em processamento de dados com Pandas.

## Consequences

- **Flexibilidade**: A arquitetura hexagonal permite que o microserviço seja facilmente adaptado para diferentes interfaces ou integrações no futuro.
- **Testabilidade**: Facilita a escrita de testes, pois a lógica de negócios é desacoplada dos adaptadores.
- **Isolamento**: Falhas ou problemas no microserviço não afetarão outras partes da aplicação.
- **Especialização**: O microserviço pode ser otimizado para processar planilhas de forma eficiente.
- **Curva de Aprendizado**: Pode haver uma curva de aprendizado para desenvolvedores não familiarizados com a arquitetura hexagonal.
- **Gerenciamento Adicional**: Requer monitoramento, logging e rastreamento adicionais para gerenciar o microserviço.
