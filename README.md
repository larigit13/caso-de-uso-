```mermaid
flowchart LR
    %% Atores
    A[<<actor>> Administrador]
    S[<<actor>> Secretário]
    F[<<actor>> Setor Financeiro]

    %% Casos de Uso
    UC1((Gestão de Pessoas<br/>(Física/Jurídica)))
    UC2((Gestão de Docentes))
    UC3((Gestão de Fornecedores))
    UC4((Gestão de Alunos))

    %% Ligações Administrador
    A --> UC1
    A --> UC2
    A --> UC3
    A --> UC4

    %% Ligações Secretário
    S --> UC1
    S --> UC2
    S --> UC4

    %% Ligações Financeiro
    F --> UC3
    F --> UC1
```
