# AngularHomework05

1) What kind of form is better for a big project?

Реактивные формы подходят, чтобы обрабатывать сложные сценарии.
Все манипуляции (проверка валидности, подписка на изменение значения и прочее) производятся в компоненте, что делает работу более гибкой, удобной и предсказуемой.
Также меньше разметки HTML.

2) Describe component lifecycle hooks: OnInit, OnChanges, AfterViewInit.

ngOnInit: вызывается один раз после установки свойств компонента, которые участвуют в привязке. Выполняет инициализацию компонента
ngOnChanges: вызывается до метода ngOnInit() при начальной установке свойств, которые связаны механизмом привязки, а также при любой их переустановке или изменении их значений. Данный метод в качестве параметра принимает объект класса SimpleChanges, который содержит предыдущие и текущие значения свойства.
ngAfterViewInit: вызывается фреймворком Angular после инициализации представления компонента, а также представлений дочерних компонентов. Вызывается только один раз сразу после первого вызова метода ngAfterContentChecked()

3) Describe built-in validation in Angular

//

4) What is formControl?

Реактивная форма Angular — объединение взаимосвязанных полей (группа), которое может содержать дочерние группы. Группа представляет собой объект FormGroup , а поле — объект FormControl.
[formControl] назначает ссылку на созданный вами экземпляр FormControl. т.е. отслеживает значение и статус проверки отдельного элемента управления формы.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.10.

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
