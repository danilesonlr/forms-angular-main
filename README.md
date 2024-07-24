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