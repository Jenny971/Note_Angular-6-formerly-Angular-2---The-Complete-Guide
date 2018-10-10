# Note_Angular-6-formerly-Angular-2---The-Complete-Guide

Note for a course on Udemy
</br>
*[Angular 6 (formerly Angular 2) - The Complete Guide](https://www.udemy.com/the-complete-guide-to-angular-2/)*

Watch in order might be a better way for this course.


### Section 1: Getting Started
- Angular: A JavaScript Framework which allows you to create reactive Single-Page-Applications
- Angular.js(Angular 1) / Angular
- [CLI](https://github.com/angular/angular-cli/wiki)
- ng new / ng serve
- file generate by ng new (first-app)
    - to use ngModel, import FormsModule in app.module.ts imports
- Course structure
- TypeScript: Superset to JavaScript
- A Basic Project Setup using Bootstrap for Styling (project-template)

### Section 2: The Basics

### Section 3: Course Project - The Basics





### Section 11: Changing Pages with Routing
- Why need router(what it does)
- Example Project *routing-start*
    <br>Will be improve through this section
- Setting up and Loading Routes
 - const appRoutes: Routes = [{ path: '', component: someComponent }];
 - RouterModule.forRoot(appRoutes)
 - <router-outlet></router-outlet>
- routerLink
- absolute path & relative path
- routerLinkActive="active"
 - [routerLinkActiveOptions]="{exact: true}"
- Trigger the navigation with code
- Use ActivedRoute for relative path
- Passing parameters to routes with path/:parameters
- Use ActivedRoute to get current parameter
- how to get updated parameter from path
- how to passing and retrieve query parameters and fragments
- Setting up Child (Nested) routes
- Configure router in a seperate file
- Protected route(unfinished)
- Passing Static Data to a Route
