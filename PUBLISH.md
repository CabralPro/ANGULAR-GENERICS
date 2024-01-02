# Angular Generics

This is a comprehensive guide on how to build and publish the Angular Generics.

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js: [Download and install Node.js](https://nodejs.org)
- npm: npm is bundled with Node.js, so you should have it installed already.

## Installation

To install the package, run the following command:

```bash
npm install
```

## Building the Package

To build the package, use the Angular CLI's build command:

```bash
npm run build angular-generics
```

This will create a `dist/angular-generics` directory with the built files.

## Testing the Package

Before publishing, it's a good idea to test the package. Run the tests with:

```bash
npm test
```

## Publishing the Package

Before you can publish, you'll need to create an account on the [NPM website](https://www.npmjs.com/).

Once you have an account, log in to NPM in your terminal:

```bash
npm login
```

Enter your username, password, and email when prompted.

Finally, publish the package:

```bash
npm run publish angular-generics
```

Congratulations! Your package is now live on NPM.