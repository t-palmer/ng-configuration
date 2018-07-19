# ng-configuration

This project is an example of Angular Environments. It was created for my article [Becoming an Angular Environmentalist](https://blog.angularindepth.com/becoming-an-angular-environmentalist-45a48f7c20d8).

## What are Angular Application Environments?

An *Angular Application Environment* is JSON configuration information that tells the build system which files to change when you use ng build and ng serve.

Let's say you have a back end REST API deployed on a server that provides services to your Angular application.
You might have a URL for your own development server, another for the test server, and another for the production server. Using Angular Application Environments you can set up three configurations and specify which to use for ng build and ng serve.

This article is targeted at Angular 6 which really improved both the ease of use and the documentation for Application Environments. The official Angular documentation for environments is here:
https://github.com/angular/angular-cli/wiki/stories-application-environments

