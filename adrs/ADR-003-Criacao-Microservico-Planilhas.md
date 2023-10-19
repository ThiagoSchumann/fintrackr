# ADR-003 - Criação de Microserviço Especializado para Processamento de Planilhas no Fintrackr

## Title

Criação de Microserviço Especializado para Processamento de Planilhas no Fintrackr.

## Status

Accepted

## Context

O Fintrackr tem uma necessidade específica de processar informações de planilhas, transformando-as em um formato desejado para integração com o sistema. Esta operação é distinta das funções de lógica de negócios principais e, portanto, requer uma abordagem arquitetural especializada.

## Decision

Criar um microserviço dedicado responsável por receber, processar e retornar informações de planilhas em um formato desejado.

## Consequences

- **Especialização**: O microserviço pode ser otimizado para processar planilhas de forma eficiente.
- **Flexibilidade**: O microserviço pode ser desenvolvido, escalado ou modificado independentemente do monólito.
- **Isolamento**: Falhas ou problemas no microserviço não afetarão o funcionamento do monólito.
- **Complexidade Adicional**: Introduz a necessidade de gerenciar a comunicação entre o monólito e o microserviço.
- **Overhead de Rede**: A comunicação entre o monólito e o microserviço pode introduzir latências.
- **Curva de aprendizado**: Os desenvolvedores podem precisar de formação ou familiarização com a gestão de microserviços.
- **Gerenciamento**: Monitoramento, logging e rastreamento adicionais serão necessários para gerenciar o microserviço.
- **Integração**: Garantir uma integração robusta e eficiente com o monólito será crucial.
