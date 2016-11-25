---
layout: post
date: 2016-11-25T12:00:00-00:00
title: "Design Patterns"
author: giovanidecusati
abstract: Padrões de código com *Design Patterns*
---
Definir um bom conjunto de classes, interfaces e métodos são um bom começo para quem quer produzir código de boa qualidade. Dificilmente encontraremos um problema que não tenha solução pronta. Basicamente, os problemas mais comuns de design são resolvidos por meio de soluções denominadas “Design Patterns”. Os patterns como são chamados permitem reduzir a complexidade do código proporcionando abstrações já prontas para o uso, fazendo com que você não precise comentar cada linha do seu código para que outros programadores entendam a sua implementação. Ao padronizar estas soluções erros comuns de implementação são reduzidos, uma vez que estes problemas vêm sido resolvidos inúmeras vezes por décadas. Além do mais, os programadores que estão familiarizados com os design patterns são capazes de facilmente reconhecer o problema e apresentar uma solução legível e que será interpretada por outros programadores. Assim, elevando o nível do seu código pondo em foco as decisões de design tomadas ao invés de tentar “reinventar” soluções inadequadas. Os Design Patterns estão categorizadas em três grupos: Creational, Structural e Behavioral.

### Creational Patterns
#### Factory
"Fornecer uma interface para criação de famílias de objetos relacionados ou dependentes sem especificar suas classes concretas."
##### Simple Factory: 
Encapsula o processo de criação de uma instância de um objeto.
* <a href="https://github.com/fabriciorissetto/design-patterns-examples/1. Creational Patterns/Simple Factory">Simple Factory</a>
##### Factory Method: 
Define uma interface para criar um objeto, deixando a classe que implementa a interface decidir qual classe instanciar.
* <a href="https://github.com/fabriciorissetto/design-patterns-examples/1. Creational Patterns/Factory Method">Factory Method</a>
##### Abstract Factory: 
Define uma interface pra criar familias de objetos sem a necessidade expor a concreta implementação. 
* <a href="https://github.com/fabriciorissetto/design-patterns-examples/1. Creational Patterns/Abstract Factory">Abstract Factory</a>

#### Builder
"Separar a construção de um objeto complexo de sua representação de modo que o mesmo processo de construção possa criar diferentes representações."
* <a href="https://github.com/fabriciorissetto/design-patterns-examples/1. Creational Patterns/Builder Pattern">Builder</a>

#### Prototype
"Especificar tipos de objetos a serem criados usando uma instância protótipo e criar novos objetos pela cópia desse protótipo."
Funciona criando cópias de um objeto já pronto (instanciado), muito útil para otimizar o processo de instanciar objetos complexos e demorados.  
* <a href="https://github.com/fabriciorissetto/design-patterns-examples/1. Creational Patterns/Prototype Pattern">Prototype</a>

#### Singleton
"Garantir que uma classe tenha somente uma instância e fornece um ponto global de acesso para a mesma." 
* <a href="https://github.com/fabriciorissetto/design-patterns-examples/1. Creational Patterns/Singleton Pattern">Singleton</a>

### Structural Patterns
#### Builder
"Separar a construção de um objeto complexo de sua representação de modo que o mesmo processo de construção possa criar diferentes representações."
* <a href="https://github.com/fabriciorissetto/design-patterns-examples/2. Structural Patterns/Bridge Pattern">Bridge Patterns</a>

#### Proxy
"Fornecer um substituto ou marcador da localização de outro objeto para controlar o acesso a esse objeto."
* <a href="https://github.com/fabriciorissetto/design-patterns-examples/2. Structural Patterns/Proxy Pattern">Proxy Patterns</a>

#### Adapter
"Converter a interface de uma classe em outra interface, esperada pelo cliente. O Adapter permite que interfaces incompatíveis trabalhem em conjunto – o que, de outra forma, seria impossível."
 * <a href="https://github.com/fabriciorissetto/design-patterns-examples/2. Structural Patterns/Adapter">Adapter</a>

#### Composite
“Compor objetos em estruturas de árvore para representar hierarquia partes-todo. Composite permite aos clientes tratarem de maneira uniforme objetos individuais e composições de objetos.”
 * <a href="http://www.codeproject.com/Articles/185797/Composite-Design-Pattern">Composite</a>

#### Decorator
"Dinamicamente, agregar responsabilidades adicionais a objetos. Os Decorators fornecem uma alternativa flexível ao uso de subclasses para extensão de funcionalidades."
 * <a href="http://www.dofactory.com/net/decorator-design-pattern">Decorator*</a>

#### Facade
"Fornecer uma interface unificada para um conjunto de interfaces em um subsistema. Facade define uma interface de nível mais alto que torna o subsistema mais fácil de ser usado."
 * <a href="http://www.dofactory.com/net/facade-design-pattern">Facade*</a>

### Behavioral Patterns
#### Strategy
"Definir uma família de algoritmos, encapsular cada uma delas e torná-las intercambiáveis. Strategy permite que o algoritmo varie independentemente dos clientes que o utilizam."
 * <a href="https://github.com/fabriciorissetto/design-patterns-examples/3. Behavioral Patterns/Strategy Pattern">Strategy</a>

#### Command
"Encapsular uma solicitação como objeto, desta forma permitindo parametrizar cliente com diferentes solicitações, enfileirar ou fazer o registro de solicitações e suportar operações que podem ser desfeitas."
 * <a href="http://www.dofactory.com/net/command-design-pattern">Command*</a>

#### Observer
"Definir uma dependência um para muitos entre objetos, de maneira que quando um objeto muda de estado todos os seus dependentes são notificados e atualizados automaticamente."
 * <a href="http://www.dofactory.com/net/observer-design-pattern">Observer*</a>

### Referências
 * GAMMA, Erich et al. Padrões de Projeto: Soluções reutilizáveis de software orientado a objetos.
 * .Net Design Patterns. Disponível em: <http://www.dofactory.com/net/design-patterns>