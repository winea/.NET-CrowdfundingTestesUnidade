# .NET-CrowdfundingTestesUnidade
Exemplos de testes de unidade .NET Core Crowdfunding

### A estrutura do projeto foi dividida seguindo o modelo MVC:

I) MVC -> Controlers

I) Vaquinha.Service -> Camada Servicos

II) Vaquinha.Domain -> Tem as Entidades responsáveis por se comunicar com o Banco de Dados

III) Vaquinha.Repository -> Tem algumas métodos

### Estrutura de Testes -> projeto Vaquinha
 
testes.common -> Biblioteca para todos os testes, através da utilização das Fixtures e possivel
realizar por exemplo View Model valido e um invalido, para realizar os testes.

### TDD
E o desenvolvimento orientado a testes, primeiro escrever um teste que ira falhar,
desenvolver um codigo para passar o teste, e refatorar o codigo
 
Na raiz do projeto adicionar o package para deixar a linguagem mais fluente, ex: Assert.true(valido)
#### dotnet add package FluentAssertions

### Teste Integracao
Testar integracao entre modulos

### Testes automatizados
Apos instalar seleniun necessario instalar chrome driver Firefox driver
