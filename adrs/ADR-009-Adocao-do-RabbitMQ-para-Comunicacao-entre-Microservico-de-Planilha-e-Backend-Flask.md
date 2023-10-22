# ADR-009 - Adoção do RabbitMQ para Comunicação entre o Microserviço da Planilha de Fatura e o Back-end Flask

## Title

Adoção do RabbitMQ para Comunicação entre o Microserviço da Planilha de Fatura e o Back-end Flask.

## Status

Accepted

## Context

Para integrar o microserviço especializado da planilha de fatura com o back-end Flask do Fintrackr, é crucial ter uma solução de mensageria confiável que facilite a comunicação assíncrona, garanta a entrega de mensagens e suporte a escalabilidade.

## Decision

Adotar o RabbitMQ como a principal solução de mensageria para garantir a comunicação eficiente entre o microserviço da planilha de fatura e o back-end Flask.

## Consequences

- **Comunicação Assíncrona**: O RabbitMQ permite que o microserviço e o back-end Flask se comuniquem de forma assíncrona, o que pode melhorar a eficiência e a resposta do sistema.
- **Garantia de Entrega**: As mensagens podem ser armazenadas e reenviadas em caso de falhas, garantindo a entrega.
- **Escalabilidade**: O RabbitMQ suporta balanceamento de carga entre múltiplas instâncias, o que pode ajudar na escalabilidade da solução.
- **Flexibilidade**: Permite a integração com outros sistemas e serviços no futuro, graças ao seu modelo de mensageria baseado em tópicos e filas.
- **Complexidade Adicional**: A introdução de uma solução de mensageria pode aumentar a complexidade do sistema e requerer monitoramento e gerenciamento adicionais.
- **Dependência Externa**: A adoção do RabbitMQ introduz uma dependência externa que precisa ser gerenciada e mantida.
