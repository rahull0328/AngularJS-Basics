# AngularJS Basics

> *Click &#9733; if you like the project. Your contributions are heartily ♡ welcome.*

<br/>

## Table of Contents

### Basics

|Sl.No|  Questions                                     |
|-----|------------------------------------------------|
| 01. |[Why to use AngularJS?](#q-why-to-use-angularjs)|
| 02. |[What are the advantage of AngularJS?](#q-what-are-the-advantage-of-angularjs)|
| 03. |[Please explain what is controller/model/view in angularjs?](#q-please-explain-what-is-controller-model-view-in-angularjs)|
| 04. |[Please tell about life cycle of angularjs application?](#q-please-tell-about-life-cycle-of-angularjs-application)|
| 05. |[What is jQLite/jQuery Lite?](#q-what-is-jqlite-jquery-lite)|
| 06. |[How to access jQLite?](#q-how-to-access-jqlite)|
| 07. |[What are the AngularJS features?](#q-what-are-the-angularjs-features)|
| 08. |[When dependent modules of a module are loaded?](#q-when-dependent-modules-of-a-module-are-loaded)|
| 09. |[What is Angular’s prefixes $ and $$?](#q-what-is-angular-s-prefixes-and)|
| 10. |[What is the role of ng-app, ng-init and ng-model directives?](#q-what-is-the-role-of-ng-app-ng-init-and-ng-model-directives)|
| 11. |[What are different ways to invoke a directive?](#q-what-are-different-ways-to-invoke-a-directive)|
| 12. |[What is restrict option in directive?](#q-what-is-restrict-option-in-directive)|
| 13. |[Can you define multiple restrict options on a directive?](#q-can-you-define-multiple-restrict-options-on-a-directive)|
| 14. |[What is scope in AngularJS?](#q-what-is-scope-in-angularjs)|
| 15. |[What is $scope and $rootScope?](#q-what-is-scope-and-rootscope)|
| 16. |[What is scope hierarchy?](#q-what-is-scope-hierarchy)|
| 17. |[What is the difference between $scope and scope?](#q-what-is-the-difference-between-scope-and-scope)|
| 18. |[How AngularJS compilation is different from other JavaScript frameworks?](#q-how-angularjs-compilation-is-different-from-other-javascript-frameworks)|
| 19. |[What are Compile, Pre and Post linking in AngularJS?](#q-what-are-compile-pre-and-post-linking-in-angularjs)|
| 20. |[Is it a good or bad practice to use AngularJS together with jQuery?](#q-is-it-a-good-or-bad-practice-to-use-angularjs-together-with-jquery)|
| 21. |[If you were to migrate from Angular 1.4 to 1.5, what is the main thing that would need refactoring?](#q-if-you-were-to-migrate-from-angular-14-to-15-what-is-the-main-thing-that-would-need-refactoring)|
| 22. |[What is the difference between one-way binding and two-way binding?](#q-what-is-the-difference-between-one-way-binding-and-two-way-binding)|
| 23. |[How would you specify that a scope variable should have one-time binding only?](#q-how-would-you-specify-that-a-scope-variable-should-have-one-time-binding-only)|
| 24. |[What directive would you use to hide elements from the HTML DOM by removing them from that DOM not changing their styling?](#q-what-directive-would-you-use-to-hide-elements-from-the-html-dom-by-removing-them-from-that-dom-not-changing-their-styling)|
| 25. |[How do you reset a $timeout, $interval(), and disable a $watch()?](#q-how-do-you-reset-a-timeout-interval-and-disable-a-watch)|
| 26. |[What is $scope in AngularJS?](#q-what-is-scope-in-angularjs)|
| 27. |[What is difference between $scope and scope?](#q-what-is-difference-between-scope-and-scope)|
| 28. |[How would you validate a text input field for a twitter username, including the @ symbol?](#q-how-would-you-validate-a-text-input-field-for-a-twitter-username-including-the-symbol)|
| 29. |[How do you hide an HTML element via a button click in AngularJS?](#q-how-do-you-hide-an-html-element-via-a-button-click-in-angularjs)|
| 30. |[How would you react on model changes to trigger some further action? For instance, say you have an input text field called email and you want to trigger or execute some code as soon as a user starts to type in their email?](#q-how-would-you-react-on-model-changes-to-trigger-some-further-action-for-instance-say-you-have-an-input-text-field-called-email-and-you-want-to-trigger-or-execute-some-code-as-soon-as-a-user-starts-to-type-in-their-email)|
| 31. |[How do you disable a button depending on a checkbox’s state?](#q-how-do-you-disable-a-button-depending-on-a-checkbox-s-state)|
| 32. |[Assuming "form" is an NgForm object, which property is used to retrieve the form values?](#q-assuming-form-is-an-ngform-object-which-property-is-used-to-retrieve-the-form-values)|

### Architecture

|Sl.No| Questions                                                             |
|-----|-----------------------------------------------------------------------|
| 33. |[What are the differences between `Provider` vs `Factory` vs `Service`?](#q-what-are-the-differences-between-provider-vs-factory-vs-service-)|
| 34. |[How do you prefer to develop the data access layer which communicate with REST service?](#q-how-do-you-prefer-to-develop-the-data-access-layer-which-communicate-with-rest-service)|
| 35. |[Which service do you use: `$http` or `$resourse` or `rest-angular`?](#q-which-service-do-you-use-http-or-resourse-or-rest-angular-)|
| 36. |[How can you configure `$http` service?](#q-how-can-you-configure-http-service)|
| 37. |[What about `q` and promises in angularjs?](#q-what-about-q-and-promises-in-angularjs)|
| 38. |[Explain Event model in angularjs?](#q-explain-event-model-in-angularjs)|
| 39. |[Do you use some sort of angular style guides?](#q-do-you-use-some-sort-of-angular-style-guides)|
| 40. |[What is dependency injection? Explain difference between inline and explicit annotation?](#q-what-is-dependency-injection-explain-difference-between-inline-and-explicit-annotation)|
| 41. |[What is auto bootstrap process in AngularJS?](#q-what-is-auto-bootstrap-process-in-angularjs)|
| 42. |[What is manual bootstrap process in AngularJS?](#q-what-is-manual-bootstrap-process-in-angularjs)|
| 43. |[How AngularJS is compiled?](#q-how-angularjs-is-compiled)|
| 44. |[What should be the maximum number of concurrent "watches"? How would you keep an eye on that number?](#q-what-should-be-the-maximum-number-of-concurrent-watches-how-would-you-keep-an-eye-on-that-number)|
| 45. |[Where should we implement the DOM manipulation in AngularJS?](#q-where-should-we-implement-the-dom-manipulation-in-angularjs)|
| 46. |[How `$digest` works?](#q-how-digest-works)|
| 47. |[What is a digest cycle in AngularJS?](#q-what-is-a-digest-cycle-in-angularjs)|
| 48. |[Explain how $scope.$apply() works?](#q-explain-how-scope-apply-works)|
| 49. |[What makes the angular.copy() method so powerful?](#q-what-makes-the-angularcopy-method-so-powerful)|
| 50. |[What is a singleton pattern and where we can find it in AngularJS?](#q-what-is-a-singleton-pattern-and-where-we-can-find-it-in-angularjs)|

### Directives

|Sl.No|  Questions                                                             |
|-----|------------------------------------------------------------------------|
| 51. |[What are directives in angularjs?](#q-what-are-directives-in-angularjs)|
| 52. |[List some built-in directives](#q-list-some-built-in-directives)
| 53. |[Explain difference between 'compile' and 'link' callbacks in directive definition](#q-explain-difference-between-compile-and-link-callbacks-in-directive-definition)
| 54. |[List types of scopes directive can have?](#q-list-types-of-scopes-directive-can-have)|
| 55. |[How Directives are compiled?](#q-how-directives-are-compiled)|
| 56. |[What are the directives in angularJS?](#q-what-are-the-directives-in-angularjs)|
| 57. |[What are different ways to invoke a directive?](#q-what-are-different-ways-to-invoke-a-directive)|
| 58. |[What is the difference between ng-show/ng-hide and ng-if directives?](#q-what-is-the-difference-between-ng-show-ng-hide-and-ng-if-directives)|
| 59. |[When creating a directive, it can be used in several different ways in the view. Which ways for using a directive do you know? How do you define the way your directive will be used?](#q-when-creating-a-directive-it-can-be-used-in-several-different-ways-in-the-view-which-ways-for-using-a-directive-do-you-know-how-do-you-define-the-way-your-directive-will-be-used)|
| 60. |[When should you use an attribute Vs an element?](#q-when-should-you-use-an-attribute-vs-an-element)|
| 61. |[What is the role of ng-app, ng-init and ng-model directives?](#q-what-is-the-role-of-ng-app-ng-init-and-ng-model-directives)|
| 62. |[How would you programatically change or adapt the template of a directive before it is executed and transformed?](#q-how-would-you-programatically-change-or-adapt-the-template-of-a-directive-before-it-is-executed-and-transformed)|
| 63. |[What is the Router directive that can be placed on elements to navigate to a new route?](#q-what-is-the-router-directive-that-can-be-placed-on-elements-to-navigate-to-a-new-route)|

### Filters

|Sl.No|  Questions                                                       |
|-----|------------------------------------------------------------------|
| 64. |[What are Filters in AngularJS?](#q-what-are-filters-in-angularjs)|
| 65. |[What are the basics steps to unit test an AngulatJS filter?](#q-what-are-the-basics-steps-to-unit-test-an-angulatjs-filter)|

### Service

|Sl.No|  Questions                                                                                           |
|-----|------------------------------------------------------------------------------------------------------|
| 66. |[What is difference between services and factory?](#q-what-is-difference-between-services-and-factory)|
| 67. |[How do you share data between controllers?](#q-how-do-you-share-data-between-controllers)|
| 68. |[How would you make an Angular service return a promise? Write a code snippet as an example?](#q-how-would-you-make-an-angular-service-return-a-promise--write-a-code-snippet-as-an-example)|
| 69. |[What is the role of services in AngularJS and name any services made available by default?](#q-what-is-the-role-of-services-in-angularjs-and-name-any-services-made-available-by-default)|
| 70. |[What is an interceptor?](#q-what-is-an-interceptor)|
| 71. |[What are common uses of an interceptor in AngularJS?](#q-what-are-common-uses-of-an-interceptor-in-angularjs)|
| 72. |[How would you implement application-wide exception handling in your Angular app?](#q-how-would-you-implement-application-wide-exception-handling-in-your-angular-app)|
| 73. |[In angular, what does the calls to the HTTP methods return?](#q-in-angular--what-does-the-calls-to-the-http-methods-return)|
| 74. |[Using the Angular Http module to make a request, which method is used to listen for an emitted response?](#q-using-the-angular-http-module-to-make-a-request--which-method-is-used-to-listen-for-an-emitted-response)|
| 75. |[An Angular class that used to create an instance that will be an argument to the request method of http is?](#q-an-angular-class-that-used-to-create-an-instance-that-will-be-an-argument-to-the-request-method-of-http-is)| 

### Miscellaneous

|Sl.No|  Questions                                                                                                  |
|-----|-------------------------------------------------------------------------------------------------------------|
| 76. |[What is the best practice to build your application](#q-what-is-the-best-practice-to-build-your-application)|
| 77. |[When it is necessary or whether it is necessary to use `$scope.$apply`](#q-when-it-is-necessary-or-whether-it-is-necessary-to-use---scope-apply)|
| 78. |[A JSON Web Token consists of?](#q-a-json-web-token-consists-of)|
| 79. |[A JWT should be signed with a secret called?](#q-a-jwt-should-be-signed-with-a-secret-called)|
| 80. |[Having the JWT token, what is the format of the Authorization header looks like?](#q-having-the-jwt-token--what-is-the-format-of-the-authorization-header-looks-like)|

<br/>

## Q. ***Why to use AngularJS?***

There are following reasons to choose AngularJS as a web development framework:

1. It is based on MVC pattern which helps you to organize your web apps or web application properly.
2. It extends HTML by attaching directives to your HTML markup with new attributes or tags and expressions
in order to define very powerful templates.
3. It also allows you to create your own directives, making reusable components that fill your needs and
abstract your DOM manipulation logic.
4. It supports two-way data binding i.e. connects your HTML (views) to your JavaScript objects (models)
seamlessly. In this way any change in model will update the view and vice versa without any DOM
manipulation or event handling.
5. It encapsulates the behavior of your application in controllers which are instantiated with the help of
dependency injection.
6. It supports services that can be injected into your controllers to use some utility code to fullfil your need.
For example, it provides $http service to communicate with REST service.
7. It supports dependency injection which helps you to test your angular app code very easily.
8. Also, AngularJS is mature community to help you. It has widely support over the internet.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. ***What are the advantage of AngularJS?***

There are following advantages of AngularJS:

1. **Data Binding** - AngularJS provides a powerful data binding mechanism to bind data to HTML elements by using scope.
2. **Customize & Extensible** - AngularJS is customized and extensible as per you requirement. You can create your own custom components like directives, services etc.
3. **Code Reusability** - AngularJS allows you to write code which can be reused. For example custom directive which you can reuse.
4. **Support** – AngularJS is mature community to help you. It has widely support over the internet. Also, AngularJS is supported by Google which gives it an advantage.
5. **Compatibility** - AngularJS is based on JavaScript which makes it easier to integrate with any other JavaScript library and runnable on browsers like IE, Opera, FF, Safari, Chrome etc.
6. **Testing** - AngularJS is designed to be testable so that you can test your AngularJS app components as easy as possible. It has dependency injection at its core, which makes it easy to test.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. ***What is jQLite/jQuery Lite?***

jQLite is a subset of jQuery that is built directly into AngularJS. jQLite provides you all the useful features of jQuery. In fact it provides you limited features or functions of jQuery.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. ***How to access jQLite?***

jQuery lite or the full jQuery library if available, can be accessed via the AngularJS code by using the element(Q. function in AngularJS. Basically, ```angular.element()``` is an alias for the jQuery function.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. ***What are the AngularJS features?***

The features of AngularJS are listed below:

1. Modules
2. Directives
3. Templates
4. Scope
5. Expressions
6. Data Binding
7. MVC (Model, View & Controller)
8. Validations
9. Filters
10. Services
11. Routing
12. Dependency Injection
13. Testing

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. ***When dependent modules of a module are loaded?***

A module might have dependencies on other modules. The dependent modules are loaded by angular
before the requiring module is loaded.
In other words the configuration blocks of the dependent modules execute before the configuration blocks of the requiring module. The same is true for the run blocks. Each module can only be loaded once, even if multiple other modules require it.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. ***What is Angular’s prefixes $ and $$?***

To prevent accidental name collisions with your code, Angular prefixes names of public objects with $ and
names of private objects with $$. So, do not use the $ or $$ prefix in your code.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. ***What are Filters in AngularJS?***

Filters are used to format data before displaying it to the user. They can be used in view templates, controllers, services and directives. There are some built-in filters provided by AngularJS like as Currency, Date, Number, OrderBy, Lowercase, Uppercase etc. You can also create your own filters.

Filter Syntax

```javascript
  {{ expression | filter}}
```

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>