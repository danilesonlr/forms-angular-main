# FormsReativos

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.



# Curiosodades


O ngForm tratata o formulario inteiro exemplo: cadastro.component.html

O ngModel trata o campo especifico exemplo: cadastro.component.html.

As rotas da aplicação são criadas no arquivo app-routing.module.ts e a tela principal mantem o path= '' 

Os imports de classe utilizado no sistema são criadas no arquivo app.module.ts

O expressao ? ou sefem navegation e colcado após uma variável para tratar um possível retorno de nulo ou undefined, sem isso, o sistema não vai presenta erro porem pode impedir que o compontente intero seja redenizado exemplo cadastro.component.html.

O ngIf e uma diretiva do Angular para realizar o if no .html exemplo cadastro.component.html.

E possivel criar uma classe .css para alterar a cor do form nas validações exemplo cadastro.component.css classe .ng-touched.ng-invalid:not(form)

E possivel criar validações no input utilizando as diretivas do Angular exemplo: cadastro.component.html required (Verificar campo preenchigo), minlength="2" (Verificar se campo possui no minimo 2 caracteres) 


A validação email do Angular possui alguns bugs por esse motivo e interessante utilizar a expressão pattern passando o regex exemplo cadastro.component.html, no exemplo está sendo usando as duas validações somente para manter o exemplo, porem não e ideal utilizar as duas validação ao mesmo tempo. 


Com o uso de Two-way data binding [()], mais conhecido como banana na caixa, é possível atribuir a uma propriedade no componente e ter o valor atualizado tanto no template como no componente.


Criar um componente ng g c components/mensagem

Para criar uma variavel dentro das tag no html e preciso utilizar a expressão # e passar o o tipo exemplo #nome="ngModel", #f="ngForm" nessas exemplos
estou criando uma variavel do tipo model para o input e uma variavel para o formulário. exemplo cadastro.component.ts

# O que directive ?

No Angular, uma diretiva é uma classe que pode modificar o comportamento de elementos no DOM. As diretivas são um dos principais recursos do Angular e permitem que você estenda o HTML com novos atributos e comportamento personalizado.


Diretivas de Componente: São na verdade componentes Angular. Um componente com um template associado é tecnicamente uma diretiva, mas geralmente nos referimos a eles como componentes.

Diretivas Atributo (Attribute Directives): Modificam o comportamento ou a aparência de um elemento, componente ou outra diretiva. Exemplo: ngClass, ngStyle.

Diretivas Estruturais (Structural Directives): Alteram a estrutura do DOM, adicionando ou removendo elementos. Exemplo: ngIf, ngFor.

Diretivas Validadoras Integradas:
    Angular fornece várias diretivas validadoras integradas que você pode usar diretamente em seus templates:

    required: Valida se o campo é obrigatório.
    minlength e maxlength: Validam o número mínimo e máximo de caracteres em um campo de texto.
    pattern: Valida se o valor do campo corresponde a uma expressão regular específica.
    min e max: Validam os valores mínimo e máximo para campos numéricos.

E possivel criar uma diretictve e exemplo maior-idade-directive.ts e está sendo usando para validar o campo nascimento cadastro.component.html

# O que e DOM?

O DOM (Document Object Model) é uma interface de programação para documentos HTML e XML. Ele representa a estrutura do documento como uma árvore de objetos que podem ser manipulados com linguagens de script, como JavaScript.

Estrutura do DOM
No DOM, cada elemento do documento é representado por um nó (node), e esses nós são organizados em uma hierarquia que forma uma árvore. Existem diferentes tipos de nós, como:

Elementos (Element nodes): Representam tags HTML (e.g., <div>, <p>, <a>).
Atributos (Attribute nodes): Representam os atributos dos elementos (e.g., class, id).
Texto (Text nodes): Representam o conteúdo textual dos elementos.
Comentários (Comment nodes): Representam comentários no código HTML.
Exemplo de Estrutura DOM
Considere o seguinte documento HTML: