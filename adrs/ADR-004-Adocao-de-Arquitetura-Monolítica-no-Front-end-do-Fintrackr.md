# ADR-004 - Adoção de Arquitetura Monolítica no Front-end do Fintrackr

## Title

Adoção de Arquitetura Monolítica no Front-end do Fintrackr.

## Status

Accepted

## Context

O projeto Fintrackr busca fornecer uma solução eficaz para o gerenciamento de finanças. Dada a pouca experiência da equipe com o desenvolvimento de front-end e a necessidade de garantir uma rápida aprendizagem e eficiência no desenvolvimento, é crucial escolher uma abordagem arquitetural que seja familiar e minimamente complexa.

## Decision

Adotar uma arquitetura monolítica para o front-end do Fintrackr.

## Consequences

- **Simplicidade**: Um front-end monolítico é mais simples de entender, desenvolver e manter, especialmente para equipes menos experientes.
- **Integração Estreita**: Todos os componentes do front-end estarão estreitamente integrados, permitindo uma melhor coesão.
- **Menor Curva de Aprendizado**: A equipe pode se concentrar em desenvolver funcionalidades em vez de gerenciar a complexidade de múltiplos serviços ou componentes independentes.
- **Desafios de Escalabilidade**: À medida que o projeto cresce, pode haver desafios associados à escalabilidade e manutenção do front-end monolítico.
