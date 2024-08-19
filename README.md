
# Soluções das Atividades de 01 a 05

Bem-vindo ao repositório das soluções das atividades de 01 a 05. Cada atividade foi projetada para fortalecer suas habilidades em C# e testar conceitos importantes. Abaixo, você encontrará uma descrição detalhada de cada atividade, as implementações realizadas e os testes desenvolvidos para garantir a funcionalidade correta.

## 📝 Atividade 01: Calculadora Básica

**Descrição:**  
Nesta atividade, foi implementada a classe `Calculator`, que realiza operações de adição simples. O método `Add` recebe dois inteiros como parâmetros e retorna a soma deles.

**Principais Conceitos:**  
- Operações matemáticas básicas
- Métodos simples

**Testes Implementados:**  
- Verificação da soma de dois números positivos.
- Verificação da soma de um número negativo e um positivo.

## 📝 Atividade 02: Verificador de Números Pares

**Descrição:**  
A classe `NumberChecker` foi desenvolvida para identificar se um número é par. O método `IsEven` retorna `true` para números pares e `false` para números ímpares.

**Principais Conceitos:**  
- Operações de módulo
- Condicionais

**Testes Implementados:**  
- Verificação de números pares.
- Verificação de números ímpares.

## 📝 Atividade 03: Analisador de Listas

**Descrição:**  
A classe `ListAnalyzer` inclui o método `FindMax`, que retorna o maior número em uma lista de inteiros. Caso a lista esteja vazia ou seja nula, o método retorna `null`.

**Principais Conceitos:**  
- Manipulação de listas
- Operações de busca e comparação

**Testes Implementados:**  
- Verificação com listas de números positivos.
- Verificação com listas de números negativos.
- Verificação de comportamento com listas vazias ou nulas.

## 📝 Atividade 04: Ordenador de Números

**Descrição:**  
A classe `NumberSorter` foi implementada para ordenar listas de inteiros. O método `SortNumbers` utiliza a função `Sort()` para ordenar os elementos da lista em ordem crescente.

**Principais Conceitos:**  
- Ordenação de listas
- Manipulação de coleções

**Testes Implementados:**  
- Verificação de listas desordenadas.
- Verificação de listas com elementos mistos.

## 📝 Atividade 05: Serviço de Cliente HTTP

**Descrição:**  
Nesta atividade, foi criada a interface `IHttpClient` para simular um cliente HTTP. A classe `HttpClientService` utiliza essa interface para realizar requisições HTTP. A classe `HttpClientWrapper` encapsula o `HttpClient` do .NET, facilitando testes e a injeção de dependências.

**Principais Conceitos:**  
- Injeção de dependência
- Uso de interfaces para abstração
- Testes de unidades com mocks

**Testes Implementados:**  
- Simulação de requisições HTTP usando NSubstitute.
- Verificação do retorno de dados de uma API simulada.

## 🚀 Como Executar os Testes

Para executar os testes das atividades:

1. Certifique-se de que o SDK do .NET esteja instalado.
2. Navegue até o diretório do projeto.
3. Execute o comando `dotnet test` para rodar todos os testes e verificar se tudo está funcionando corretamente.

## 🛠️ Tecnologias Utilizadas

- **C#**
- **.NET Core**
- **XUnit** para testes unitários
- **NSubstitute** para mocks e simulações

## 📂 Estrutura do Projeto

```
Atividades_Resolvidas_01_05/
├── Atividade01/
├── Atividade02/
├── Atividade03/
├── Atividade04/
├── Atividade05/
└── README.md
```

