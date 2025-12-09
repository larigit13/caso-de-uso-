# caso-de-uso-

## Diagrama de Caso de Uso – Gestão de Pessoas, Docentes, Fornecedores e Alunos

```mermaid
%% Diagrama de Caso de Uso
usecaseDiagram

actor Administrador
actor Secretario as "Secretário"
actor Financeiro as "Setor Financeiro"

usecase (Gestão de dados de Pessoas\n(Física e Jurídica)) as UC_Pessoas
usecase (Gestão de dados de Docentes) as UC_Docentes
usecase (Gestão de dados de Fornecedores) as UC_Fornecedores
usecase (Gestão de dados de Alunos) as UC_Alunos

Administrador --> UC_Pessoas
Administrador --> UC_Docentes
Administrador --> UC_Fornecedores
Administrador --> UC_Alunos

Secretario --> UC_Pessoas
Secretario --> UC_Docentes
Secretario --> UC_Alunos

Financeiro --> UC_Fornecedores
Financeiro --> UC_Pessoas
```
