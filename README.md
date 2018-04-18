# React support for Angular

[![npm version](https://badge.fury.io/js/%40angular-react%2Fcore.svg)](https://www.npmjs.com/package/@angular-react/core)

Industry trends, organizational pressures, and other factors can lead to mandates regarding the use of component libraries or migration from one technology to another.  In the case of [Office UI Fabric][fab], where its use is required, the client must be written in React (there is no Angular component library for the latest version).  Rewrite from Angular to React may be cost-prohibitive or ill advised for other reasons.  

Use of Angular-React allows consuming any React elements, but specifically Office UI Fabric, within an Angular [2+] application.  The library of wrappers for Office UI Fabric simplifies the use of these components with Angular.  However, any React code can make use of the custom Angular-React renderer.

#### Quick links
[@angular-react/fabric](https://www.npmjs.com/package/@angular-react/fabric) |
[Documentation, quick start, and guides][ard] |
[Demo][ard-demo] |
[Contributing](https://github.com/benfeely/angular-react/blob/master/CONTRIBUTING.md) |
[StackBlitz Template](https://stackblitz.com/edit/angular-react) |
[Office UI Fabric](https://developer.microsoft.com/en-us/fabric)

### Typical Use Cases
- Use React component libraries with Angular
- Incrementally rewrite an Angular application into React (moving from atomic/leaf nodes upward into full features/pages until the entire app is re-written)

### Getting started

See our [Getting Started Guide][getting-started]
if you're building your first project with Angular-React.

If you'd like to contribute, you must follow our [contributing guidelines](https://github.com/angular/material2/blob/master/CONTRIBUTING.md).
You can look through the issues (which should be up-to-date on who is working on which features and which pieces are blocked) and make a comment.

[ard]: https://benfeely.github.io/angular-react
[ard-demo]: https://benfeely.github.io/angular-react
[getting-started]: https://benfeely.github.io/angular-react/docs/getting-started
[fab]: https://developer.microsoft.com/en-us/fabric
