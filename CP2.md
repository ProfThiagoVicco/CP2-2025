CP2 - Advanced Business Development with .NET - 2025
===========================

Este projeto faz parte do CP2 da disciplina Advanced Business Development with .NET e tem como objetivo criar uma API RESTful, usando .NET 8 e banco Oracle, aplicando Clean Architecture e Domain-Driven Design (DDD), com foco em solucionar um desafio real da empresa Mottu.

🎯 O QUE VOCÊ DEVE FAZER
===========================

✅ Criar um documento complementar com a ideia do projeto. Esse documento ajudará a contextualizar o código entregue e demonstrar a capacidade de análise e planejamento do grupo.

✅ Criar uma API RESTful que contenha:
- CRUD completo para pelo menos 2 entidades do domínio (GET, POST, PUT, DELETE)
- UTILIZAR RELACIONAMENTOS
- Respostas HTTP apropriadas: 200, 201, 204, 400, 404, etc.

✅ Aplicar boas práticas de desenvolvimento:
- Separação por camadas: Domain, Application, Infrastructure, Presentation
- DTOs, validações e regras de negócio aplicadas nas entidades
- AutoMapper + MappingConfig
- Entidades ricas (comportamento + validação de negócio)

✅ Banco de Dados:
- Utilização do Oracle via EF Core
- Versionamento com Migrations
- Uso de variáveis de ambiente para strings de conexão (NUNCA subir a string no repositório)

✅ Documentação:
- Swagger/OpenAPI devidamente configurado e funcional

✅ Organização do Repositório:
- README contendo:
  - Descrição do projeto
  - Rotas disponíveis
  - Tecnologias utilizadas
  - Instruções de execução
  - Nome e RM dos integrantes

🎯 Esclarecimento: CP2 x Challenge Final
===========================

O CP2 tem como objetivo a entrega de um MVP (Produto Mínimo Viável) da aplicação que vocês irão desenvolver de forma mais completa no challenge final da disciplina. Ou seja:

🔹 O CP2 é uma primeira versão funcional, com foco em mostrar a ideia e a estrutura base do sistema. É como um protótipo evoluído, onde queremos ver:

A proposta de solução para o problema da Mottu

A aplicação de boas práticas como Clean Architecture, DDD, e uso correto do Oracle com EF Core

O domínio já sendo modelado com comportamento

Um CRUD básico com documentação

🔹 Já o challenge é a entrega final e mais completa, com mais funcionalidades, refinamentos técnicos e melhorias que vocês não tiveram tempo de implementar no MVP.

Portanto, o que estou pedindo no CP2 é uma versão inicial, não o projeto pronto e completo do challenge. A ideia é validar a direção do grupo, a aplicação dos conceitos e o nível de entendimento técnico até aqui.


📊 O QUE SERÁ AVALIADO
============================

| Critério                               | Pontos |
|----------------------------------------|--------|
| Funcionalidades da API (CRUD, REST)    | 30     |
| Arquitetura aplicada (DDD, Clean)      | 20     |
| Banco Oracle + Migrations              | 15     |
| Documentação Swagger                   | 10     |
| Uso de MappingConfig + DTO             | 10     |
| Qualidade do Código + Boas práticas    | 10     |
| Organização do Repositório             | 5      |
| **Total**                              | **100**|

💡 DICAS IMPORTANTES
===============================

- O projeto deve ser ORIGINAL. Não use o exemplo da aula.
- Escreva código limpo e bem organizado.
- Proteja dados sensíveis. Nunca suba senhas ao GitHub.
- IA pode ajudar, mas entenda cada linha do seu código.

👥 GRUPO
===============================

- RM12345 - Nome Completo
- RM12346 - Nome Completo
- RM12347 - Nome Completo

📚 TECNOLOGIAS SUGERIDAS
===============================

- .NET 8 / ASP.NET Core Web API
- EF Core + Oracle
- Swagger / Swashbuckle
- AutoMapper
- FluentValidation (opcional)
- Docker (opcional)

📅 PRAZO DE ENTREGA
===============================

18 de maio de 2025

Entrega via portal FIAP com link do GitHub


“Faça o teu melhor, na condição que você tem, enquanto você não tem condições melhores, para fazer melhor ainda.”
— Mario Sergio Cortella
