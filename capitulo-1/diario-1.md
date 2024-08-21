# Do início!

## Definição

Angular é um framework frontend para Javascript, que tem como intuito modernizar e facilitar o desenvolvimento web frontend. 

Além disso, também é uma coleção de ferramentas e features que auxiliam o desenvolvedor ao longo do processo de criação de software (CLI, ferramentas de debugging, plugins de IDE, etc).

## Por que Angular?

A real é que **não precisamos** do Angular pra aplicações simples. A parada aqui é quando é adicionada mais complexidade ao projeto.

Uma vantagem que ele traz é a escrita de **código declarativo**, ao invés de código imperativo como no Javascript vanilla.

Lembrando que:

- Código Declarativo: Foca no o *quê* deve ser feito, especificando o resultado desejado sem detalhar como alcançá-lo. Exemplos incluem SQL e HTML.

- Código Imperativo: Foca no *como* realizar uma tarefa, detalhando os passos necessários para alcançar o resultado. Exemplos incluem C e Java.

No Angular, por exemplo, usamos uma abordagem mais declarativa com templates e bindings, enquanto no TypeScript (ou JavaScript), podemos usar uma abordagem imperativa para lógica de programação.

Outra vantagem é a separação do conteúdo por árvores de componentes, trazendo organização de código. Com a quebra em componentes (ou componentização), podemos diminuir a complexidade e dependência, trazendo responsabilidade a blocos simples e usar eles apenas quando necessário.

Mais uma vantagem é o uso da orientação a objetos trazido pelo Typescript.

## Criando uma aplicação Angular

Na criação de uma aplicação é usado o Angular CLI. Mais detalhes podem ser encontrados nesse [link](https://angular.dev/tools/cli/setup-local).

Mas resumindo:

1- Instale o node.js
2- Instale o CLI com o comando ``` npm install -g @angular/cli ```
3- Navegue até a pasta do local onde você quer criar o projeto
4- Para criar, use o comando ``` ng new nome-projeto ```
5- Confirme as opções padrão (Caso você não queira algo específico)
6- Para rodar a aplicação, suba até a pasta do projeto e use o comando ``` npm start ```

## Extensões para VSCode recomendadas

- Angular Language Service
- Angular Essentials