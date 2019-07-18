## ANGULAR APPLICATION
### PREREQUIREMENTS

Angular application needs to following tools be installed:

* [Node.js](https://nodejs.org/en/) 6.9+ with npm 3.10+
* [Typescript](https://www.typescriptlang.org/) 2.0+
* [yarn](https://yarnpkg.com/en/)

### RESTORE PACKAGES

Locate to the Angular folder, open a command line and run the following command to restore packages:
```
yarn
```

We suggest to use yarn because npm has some problems. It is slow and can not consistently resolve dependencies, yarn solves those problems and it is compatible to npm as well.

### RUN THE APPLICATION

Open command line and run the following command:
```
npm start
```
Once the application compiled, you can browse http://localhost:4200 in your browser. This also has HMR (Hot Module Replacement) enabled. You can use the following command (instead of npm start) to enable HMR on development time:

```
npm run hmr
```

## LOGIN

All ready.. just run your solution to enter to the login page