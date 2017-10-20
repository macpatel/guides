---
title: Angularjs Interview Questions
---
## Angularjs Interview Questions
Below are some set of common interview questions for AngularJS.

### What is AngularJS?
AngularJS is javascript framework developed by Developed and maintained by Google.It helps us to create SPA(Single Page Application).

### What is Directive?
At a high level, directives are markers on a DOM element (such as an attribute, element name, comment or CSS class) that tell AngularJS's HTML compiler ($compile) to attach a specified behavior to that DOM element (e.g. via event listeners), or even to transform the DOM element and its children.

### What is Component?
In AngularJS, a Component is a special kind of directive that uses a simpler configuration which is suitable for a component-based application structure.It is introduced to make it easy to migrate to Angular 2.

### What are watchers?
Watchers are events attacehed to $Scope model. Whenever the scope model changes, the change is ditected by angular and it will execute digest cycle. Digest cycle excutes the listener function on the watcher.

Below code shows you how to setup watcher.

````JavaScript
$scope.$watch('aModel', function(newValue, oldValue) {
  //update the DOM with newValue
});
````

#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->
