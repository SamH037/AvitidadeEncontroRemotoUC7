# Sistema de Cadastro de Clientes

Repositório responsavel para o sistema de cadastro de clientes, Pessoa Física e Jurídica da empresa ClientLab

## 🚀 Funções

- Cadastra pessoa fisica, maior de 18, data de nascimento, CPF, edeceço e rendimento;
- Cadastra pessoas jurídicas, com razão social, CNPJ, rendimento e endereço;
- Calcula imposto a ser pago com base no rendimento informado, cada tipo de pessoa paga um imposto diferente;
- Salva registros de pessoas físicas em arquivos .txt;
- Salva registros de pessoas jurídicas em arquivos .csv.
- Lista clientes já cadastrados;

### 📋 Requisitos

### Editor
[Visual Studio Code](https://code.visualstudio.com) 
### Linguagens
- [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)
- [.NET](https://dotnet.microsoft.com)
#### Extensões
- C#
- C# Snippets
- C# Extensions
- C# XML Documentation
- Omnisharp
- Bracket Pair Colorizer

### 🔧 Organização do projeto
Ferramenta Trello

## ⚙️ Requisitos de instalação

- Utilizar o GitHub;
- Instalar o Git Bash;
- Instalar ferramentas .NET.

### 🔩 Como executar
1- Clone o repositório para sua maquina
```bash
> git clone https://github.com/SamH037/AvitidadeEncontroRemotoUC7
```

2- Abra o Repositório
```bash
> cd cadastro-de-clientes
```
3- Execute a aplicação pelo VSCode
```bash
>dotnet run
```

## Erros Comuns

### Digitar Letras no lugar do CPF
- Encerre o programa, e refaça o cadastro
### Erro com data de nascimento
- O formato de data a ser cadastrado no sistema não é o formato brasileiro, use o formato AAAA-MM-DD
### Informar "Sim" ou "Não" ao informar se endereço é Comercial
- Deve-se informar S ou N

## ✒️ Autores

* **Odirlei** - Professor
* **Samuel Hipólito** - Aluno
