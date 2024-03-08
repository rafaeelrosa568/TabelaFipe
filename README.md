# API Tabela FIPE de Veículos

Este projeto é uma API backend que provê dados sobre a Tabela FIPE de veículos, permitindo aos usuários consultar preços médios de veículos no mercado brasileiro. O sistema foi desenvolvido durante um curso na Alura, focando em práticas de desenvolvimento de APIs.

## Tecnologias Utilizadas

- Spring Boot
- Maven
- JPA/Hibernate

## Funcionalidades

A API oferece os seguintes endpoints:

- **GET /veiculos** - Lista todos os veículos disponíveis na base de dados.
- **GET /veiculos/{codigoFipe}** - Retorna detalhes de um veículo específico baseado no código FIPE.

## Como Instalar e Rodar o Projeto

Para instalar e executar esta API localmente, siga os passos abaixo:

1. Clone o repositório do projeto para sua máquina local usando o seguinte comando no terminal:

```bash
git clone https://github.com/seu-usuario/tabela-fipe-api.git
