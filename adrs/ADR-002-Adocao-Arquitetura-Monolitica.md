# ADR-002 - Adoção de Arquitetura Monolítica para a Lógica de Negócios Principal do Fintrackr

## Title

Adoção de Arquitetura Monolítica para a Lógica de Negócios Principal do Fintrackr.

## Status

Accepted

## Context

O projeto Fintrackr visa fornecer uma solução robusta para o gerenciamento de finanças. Uma parte significativa do sistema é composta por operações de cadastro e lógica de negócios. Para acomodar essas necessidades de maneira coesa, é essencial considerar uma abordagem arquitetural que possa integrar eficientemente esses componentes.

## Decision

Adotar uma arquitetura monolítica para a lógica de negócios principal e cadastros do Fintrackr.

## Consequences

- **Consistência**: Um monólito oferece uma base de código unificada, o que pode simplificar o desenvolvimento e a manutenção.
- **Performance**: Com todos os componentes principais no mesmo processo, as latências de comunicação são minimizadas.
- **Simplicidade**: Menos preocupações com a comunicação entre serviços.
- **Escalabilidade Vertical**: O monólito pode ser escalado verticalmente, mas pode haver limitações na escalabilidade horizontal.
- **Potencial de Acoplamento**: Pode haver riscos de acoplamento apertado entre os módulos ao longo do tempo.
- **Curva de aprendizado**: Desenvolvedores familiarizados com microserviços podem precisar de tempo para se adaptar à abordagem monolítica.
- **Flexibilidade**: Modificações no sistema podem requerer reimplantações completas em vez de serviços individuais.
- **Manutenção**: À medida que o projeto cresce, a manutenção pode se tornar mais desafiadora devido ao tamanho do código base.
