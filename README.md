# Future-Proofing Angular 1 for Angular 2

This is just a quick reference guide to blogs and articles that can give recommendations and best practices to best prepare an Angular 1 application for Angular 2. 

## TLDR;
You should consider all of the following when preparing your application for an eventual Angular 2+ upgrade:
* Use component-based design
* Convert controllers to components
* Use ES6  (Ecmascript 2015)
* Remove/Avoid $scope
* Use ES6 modules over angular#module where possible
* Use angular#service over angular#factory (using ES6 classes)
* Use Rule of 1: One component per file

## Reference Material
I don't claim to know very much about AngularJS, but I'm providing some resources of the various blogs/articles that show practices to write components in Angular 1 and other future proofing techniques. Unfortunately, you will find some inconsistencies between them all in attempting to put together a coherant plan of attack. Use your best judgement, but hopefully after reviewing all the references an approach will form to best write the application for future upgrades.

### Writing Components
[Simple example of converting to component-based design](http://juristr.com/blog/2016/06/from-ngcontroller-to-components/)

[Example of 1.4 directive to 1.5 component to 2.0 component](https://www.sitepoint.com/upgrade-to-angular-components/)

[Example of create a Angular 1.5 component-based application] (http://blog.grossman.io/angular-1-component-based-architecture-2/)

[Short Example of writing a 1.5 component and short discussion on lifecycle hooks](https://tests4geeks.com/build-angular-1-5-component-angularjs-tutorial/)

### Future Proofing Best Practices
[Angular 1 best practices in preparation of Angular 2](https://www.excella.com/insights/preparing-to-migrate-from-angular-1-x-to-angular-2-0)

[ES6, Components, and other practices for future proofing](http://orizens.com/wp/topics/5-steps-to-prepare-your-angular-1-code-to-angular-2/)

[Components, ES6, modules, removing $scope, etc. ](https://www.airpair.com/angularjs/posts/preparing-for-the-future-of-angularjs)

