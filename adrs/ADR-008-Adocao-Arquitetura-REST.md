# ADR-008 - Adoção da Arquitetura REST

## Title

Adoção da Arquitetura REST para Comunicação entre Front-end e Back-end Flask.

## Status

Accepted

## Context

O Fintrackr possui componentes de front-end e um back-end construído com Flask. Para garantir uma comunicação eficiente e padronizada entre esses dois componentes, é necessário escolher uma arquitetura de comunicação apropriada.

## Decision

Adotar a arquitetura REST (Representational State Transfer) como a principal forma de comunicação entre o front-end e o back-end Flask do Fintrackr.

## Consequences

- **Padronização**: A arquitetura REST fornece um conjunto padronizado de convenções para a criação de APIs.
- **Escalabilidade**: REST é stateless, o que facilita a escalabilidade horizontal do sistema.
- **Flexibilidade**: Permite que o front-end e o back-end Flask se comuniquem de maneira eficiente.
- **Interoperabilidade**: Facilita a integração com sistemas externos ou de terceiros.
- **Simplicidade e Eficiência**: REST utiliza os métodos HTTP padrão e é baseado em recursos, tornando-o intuitivo e eficiente.
- **Desacoplamento**: Permite que o front-end e o back-end Flask evoluam separadamente, desde que a API permaneça consistente.
- **Conformidade com Padrões da Web**: REST é amplamente adotado na web, e muitas ferramentas e bibliotecas suportam essa arquitetura.
- **Considerações de Segurança**: Como qualquer API exposta, medidas de segurança adequadas, como autenticação e autorização, devem ser implementadas ao comunicar entre o front-end e o back-end Flask.
