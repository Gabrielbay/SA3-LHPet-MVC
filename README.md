# LH Pet — Implantação Web MVC (SA3 Atividade 3)

Codificação Back-End (SENAI) — aplicação Web .NET com arquitetura MVC para o
sistema de controle interno da clínica veterinária LH-Pets. Ainda sem banco
de dados: os clientes e fornecedores são instanciados em memória no
`HomeController` e exibidos na view por meio do `ViewBag`.

## Estrutura

- `Models/Cliente.cs` — Id, Nome, Cpf, Email, Paciente
- `Models/Fornecedor.cs` — Id, Nome, Cnpj, Email
- `Controllers/HomeController.cs` — cria as listas de clientes e fornecedores e as envia para a view via `ViewBag`
- `Views/Home/Index.cshtml` — exibe as duas listas em tabelas Bootstrap

## Como executar

```
dotnet run
```

Acesse a URL exibida no terminal para ver as listas de clientes e
fornecedores.
