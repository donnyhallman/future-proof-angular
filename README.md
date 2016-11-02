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
I don't claim to know very much about AngularJS, but I'm providing some resources of the various blogs/articles that show practices to write components in Angular 1 and other future proofing techniques. Unfortunately, you will find some inconsistencies between them all in attempting to put together a coherent plan of attack. Use your best judgement, but I hope that after reviewing all the references an approach will form to best write the application for future upgrades.

### Writing Components
[Simple example of converting to component-based design](http://juristr.com/blog/2016/06/from-ngcontroller-to-components/)

[Example of 1.4 directive to 1.5 component to 2.0 component](https://www.sitepoint.com/upgrade-to-angular-components/)

[Example of create a Angular 1.5 component-based application] (http://blog.grossman.io/angular-1-component-based-architecture-2/)

[Short Example of writing a 1.5 component and short discussion on lifecycle hooks](https://tests4geeks.com/build-angular-1-5-component-angularjs-tutorial/)

### Future Proofing Best Practices
[Angular 1 best practices in preparation of Angular 2](https://www.excella.com/insights/preparing-to-migrate-from-angular-1-x-to-angular-2-0)

[ES6, Components, and other practices for future proofing](http://orizens.com/wp/topics/5-steps-to-prepare-your-angular-1-code-to-angular-2/)

[Components, ES6, modules, removing $scope, etc. ](https://www.airpair.com/angularjs/posts/preparing-for-the-future-of-angularjs)

### Large Example/Tutorial
The following goes through the creation of an Angular 1.5 application using ES6. It uses multiple videos with some associated text to go through example. I'd imagine it would take a while to go through (as I didn't take the time to watch it all). However, it looks to be be a good example as well for showing the type of approach we should take with Angular to best future-proof our application(s).

[Angular 1.5 with ES6 Tutorial](https://thinkster.io/angularjs-es6-tutorial)
