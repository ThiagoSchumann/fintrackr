# ADR-010 - Adoção do SQLAlchemy para Comunicação com o Banco de Dados no Flask

## Title

Adoção do SQLAlchemy como ORM para Comunicação com o Banco de Dados no Flask.

## Status

Aceito

## Context

O Fintrackr, construído usando Flask, precisa interagir de maneira eficiente e segura com o banco de dados. A escolha de uma estratégia ou ferramenta adequada para esta comunicação é crucial para a robustez e manutenibilidade do sistema.

## Decision

Adotar o SQLAlchemy, um ORM popular e amplamente utilizado na comunidade Flask, como a principal ferramenta para estabelecer a comunicação entre a aplicação Flask e o banco de dados.

## Consequences

- **Abstração**: O SQLAlchemy permite que a equipe de desenvolvimento trabalhe com o banco de dados usando a linguagem Python, abstraindo muitos detalhes do SQL.
- **Segurança**: O SQLAlchemy tem proteções embutidas contra injeções SQL, reduzindo o risco desses tipos de ataques.
- **Produtividade**: Facilita operações comuns do banco de dados, como inserções, atualizações, leituras e exclusões, através de uma API intuitiva.
- **Portabilidade**: O SQLAlchemy suporta vários sistemas de gerenciamento de banco de dados, tornando mais fácil mudar para um banco de dados diferente no futuro, se necessário.
- **Complexidade Adicional**: Apesar de ser poderoso, pode haver uma curva de aprendizado inicial para desenvolvedores não familiarizados com o SQLAlchemy ou seus padrões.
