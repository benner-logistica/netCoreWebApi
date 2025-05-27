# Desafio Técnico - .NET Core

## Objetivo
Criar uma API simples de gerenciamento de contatos com ASP.NET Core.

## Rodando o projeto

1. Restaure os pacotes:
```bash
dotnet restore
```

2. Execute as migrações e crie o banco:
```bash
dotnet ef migrations add InitialCreate
dotnet ef database update
```

3. Execute a aplicação:
```bash
dotnet run
```

Acesse `http://localhost:5000/swagger` para testar os endpoints.
