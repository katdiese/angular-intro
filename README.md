*Why learn Angular JS over other frameworks like Ember, Backbone, Knockout, etc?
>Angular JS is a whole framework that deals very well with a large, complex amount of data

*People have some very strong opinions about Angular. What are 3 common complaints people have about Angular?
  1. Angular forces you to work in one specific way
  2. The language and structure in Angular mimicks the needs of those who work in the back end
  3. Angular must parse the entire DOM to discover all nodes and attribute values, which is an expensive process especially for mobile

*Is Angular an MVC framework?
>Yes

*Turn to the Angular docs. Find ng-app. What is it and what does it do? What does ng stand for?

>ng-app is the easiest, most common way to bootstrap an AngularJS app. designates the root element of the app (on the body or html tags. ng is for Angular

*What does ng-model do?

>binds an input, select, textarea, or other form control to a property on the scope

*What is "dirty checking"?
>checks whether a value has changed that hasn't been changed across the app

*Find a way to set the initial value of "name" as "BoJack" (without writing a controller).

>include ng-init="name='BoJack'" in the input

*What are those {{ }} expressions? Are they Handlebars?

>Not handlebars, displays the value of whichever input is tied to what's inside of curly braces

*Explain what two-way data binding is.

>Angular templates will automatically update when data changes, when data changes, the change is immediately updated in view, if changes in view, immediately updated in the controller

*BONUS: Research the $digest loop

>Where angular checks if there any changes to all variables watched by all the $scopes
>Code that runs inside the angular event loop, the $watch list and the $evalAsync list
>$watch: register a callback function expected to be called when an event happens in the page