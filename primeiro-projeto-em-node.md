# Primeiro projeto em node

Até então, temos uma pasta com um arquivo de olá mundo. Dado que tudo deu certo, sejamos mais ambiciosos: criemos um novo projeto.

### Por onde começar

A primeira coisa a se fazer para ter um projeto em node é inicializá-lo, através do seguinte comando:

```
npm init
```

Este comando lhe fará muitas perguntas à respeito de como você prefere configurar seu novo projeto. No momento, estas informações não são importantes, podemos deixar que o `npm` escolha pra gente, pressionando enter a cada pergunta que ele nos fizer. Depois de todas as perguntas feitas, teremos um novo arquivo no nosso projeto: o **package.json**. Voltaremos nesse arquivo em breve, depois de entendermos alguns conceitos importantes por trás dele.

## Muito prazer, npm

O npm é uma ferramenta adicional ao node, que é instalada junto com ele. Portanto, quando instalamos node, instalamos o npm junto. Para quê serve o npm? Podemos entendê-lo como a **ferramenta de build** \(mais à respeito disso no apêndice\) oficial do node. Como ferramenta de build, o npm se torna fundamental para um projeto, pois ele é responsável por muitas tarefas que envolvem o desenvolvimento de um projeto. Dentre outras coisas, o npm ajuda bastante no seguinte:

### Gestão de dependências

Todo projeto de software atual possui dependências externas. Podemos entender _**dependência**_ como todo código de terceiros que utilizamos para não reinventar todas as rodas que envolvem construir um software. Refletindo rapidamente, poderíamos citar alguns exemplos reais de bibliotecas node que podem ser dependência de um projeto:

* Uma biblioteca de acesso à banco de dados: mongoose
* Uma biblioteca de manipulação de datas: moment
* Uma biblioteca de execução de testes: mocha

Todo novo projeto de software tem problemas comuns que precisam de resolução e, é bem provável que alguém já tenha resolvido este problema antes de você no mundo open source. Podemos utilizar estas soluções disponíveis mundo afora através da gestão de dependências fornecida pelo npm. Mais adiante, veremos em mais detalhe como o npm gerencia dependências.

### Automação de tarefas

O npm possui definições de scripts. Isso é dizer que podemos automatizar tarefas repetitivas do projeto de uma maneira simples e organizada utilizando o npm. Alguns exemplos de tarefas poderiam ser: lint de código, execução de testes, atualização de documentação, etc. Se você não é familiar com estas tarefas, não se preocupe, isso não é importante agora e veremos algumas delas mais pra frente.


