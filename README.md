# ihcux-racha-ai-blazor-
# RachaAi — Dashboard Financeiro em Blazor
## 👤 GRUPO 
*Nome:* Gabriel Ribeiro -  RA: 325127609
*Curso:* (++++++++++++++++++)


Projeto desenvolvido para a disciplina de Interação Humano Computador e UX.

O sistema apresenta um dashboard de divisão de gastos compartilhados, permitindo visualizar:
- Total a receber
- Total a pagar
- Saldo geral
- Lista de grupos de despesas

---

# Tecnologias Utilizadas

- .NET 10
- Blazor WebAssembly
- Bootstrap 5
- C#

---

# Estrutura do Projeto

```plaintext
/Models
    Grupo.cs

/Pages
    Dashboard.razor

/Shared
    GrupoCard.razor

## Dificuldade Técnica Adicional

Outra dificuldade encontrada foi entender o sistema de roteamento e renderização do Blazor WebAssembly.

Durante o desenvolvimento, a página Dashboard.razor compilava corretamente, porém não aparecia no navegador. O problema estava relacionado à configuração do App.razor e à estrutura do MainLayout, que precisava conter o @Body para renderizar as páginas.

Esse processo ajudou a compreender melhor:
- como o Blazor gerencia rotas com @page
- como funciona o Router
- a importância do Layout na exibição das páginas
- a relação entre componentes e renderização no ciclo de vida do Blazor
