# PennyWise

PennyWise é um sistema de gestão financeira open source desenvolvido em Kotlin, utilizando o framework Micronaut. Este projeto visa transformar a gestão financeira tradicional em uma solução digital robusta, escalável e fácil de usar.

## Objetivo

O objetivo do PennyWise é fornecer uma ferramenta para gerenciar entradas, saídas e saldos financeiros de forma eficiente. O sistema será construído com base na Clean Architecture, garantindo manutenibilidade e facilidade de extensão para futuras integrações, incluindo um frontend.

## Tecnologias Utilizadas

- **Linguagem**: Kotlin
- **Framework Backend**: Micronaut
- **Gerenciamento de Dependências e Build**: Gradle
- **Banco de Dados**: Micronaut Data

## Funcionalidades

1. **Gestão de Entradas e Saídas**: Permite o registro de transações financeiras com suporte a múltiplos lançamentos por período.
2. **Cálculo Automático de Saldo**: Atualiza o saldo automaticamente conforme novas transações são registradas.
3. **Relatórios Financeiros**: Gera relatórios detalhados e gráficos sobre a situação financeira.
4. **Previsões de Saldo**: Calcula previsões de saldo com base em entradas e saídas programadas.

## Estrutura do Projeto

O projeto segue a Clean Architecture, que se divide nas seguintes camadas:

- **Domínio**: Contém as entidades e regras de negócios.
- **Casos de Uso**: Orquestra as interações entre as entidades e outras camadas.
- **Interfaces de Entrada**: Implementa os controladores e a API REST.
- **Interfaces de Saída**: Implementa os repositórios e a persistência de dados.

## Padrões de Design

O PennyWise incorpora diversos padrões de design para garantir qualidade e manutenibilidade:

- **Factory Pattern**
- **Repository Pattern**
- **Strategy Pattern**
- **Builder Pattern**
- **Adapter Pattern**

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests. Para detalhes sobre como contribuir, consulte o arquivo [CONTRIBUTING.md](./CONTRIBUTING.md).

## Licença

Este projeto é licenciado sob a [Apache License 2.0](./LICENSE).

## Contato

Para mais informações, entre em contato com os mantenedores do projeto ou abra uma issue no repositório.
