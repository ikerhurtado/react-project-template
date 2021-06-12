# React project (front-end only) template

This is a project template intended to serve as a starting point if you want to bootstrap a React front-end only project.

## Features

### Minimal setup
- [Webpack](https://webpack.js.org/) (v5)
- [Babel](https://babeljs.io/) with [preset-env](https://babeljs.io/docs/en/babel-preset-env)

### Minimal + linter setup
- [ESLint](https://eslint.org/) with:
  - [React pluging](https://www.npmjs.com/package/eslint-plugin-react)
  - [Javascript Standard Style](https://standardjs.com/)

### Minimal + linter + unit testing setup
- [Jest](https://jestjs.io) with [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)


## Running the app

```
# install dependencies
npm install

# run in dev mode on port 8080
npm run dev

# generate production build
npm run build
```

## Linting

You can run the tool manually from the command line on the project folder:

```
npx eslint . // diagnose: all errors are shown
npx eslint . --fix // some errors found are fixed
```

## Testing

### Jest with React Testing Library

```
npm run test
```