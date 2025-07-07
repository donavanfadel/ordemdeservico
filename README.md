# Sistema de Controle de Ordens de Serviço #
Aplicação web para registro, acompanhamento e gestão de ordens de serviço, desenvolvida em ASP.NET Core MVC. Permite o controle completo de solicitações de atendimento, com integração a procedimentos armazenados no banco de dados e geração de relatórios para análise no Power BI.

---

## Funcionalidades
- Cadastro de ordens de serviço com cliente, descrição e status
- Listagem dinâmica com dados vindos de stored procedures (SQL Server)
- Edição e exclusão com persistência via procedures
- API REST para consumo externo dos dados
- Integração com Power BI para criação de dashboards e relatórios interativos
- Interface amigável com validações de formulário e mensagens de erro

---

## Tecnologias
- ASP.NET Core MVC (.NET 9)
- SQL Server com Stored Procedures
- Entity Framework Core para contexto de dados
- API RESTful com retorno em JSON
- Power BI para visualização e análise de dados
- Bootstrap para responsividade e layout moderno
