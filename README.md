# Welcome to my ALX Frontend JavaScript repository!
-------------
This repository specifically focuses on frontend development with __JavaScript__. 
It contains __exercises__, __projects__, and __resources__ developed to provide 
a structured practical learning approach of __JavaScript frontend development__.
Projects like  `ES6 Basics`, `ES6 Promises`, `ES6 classes`,
`ES6 data manipulation` and `Typescript` are to be covered in details.

__Prerequisites__
In this repository, the following prerequisites must be installed:

- Node.js: __JavaScript__ runtime environment.
- npm: Node package manager.
- babel.config.js

```
module.exports = {
  presets: [
    [
      '@babel/preset-env',
      {
        targets: {
          node: 'current',
        },
      },
    ],
  ],
};

```
- .eslintrc.js

```
module.exports = {
  env: {
    browser: false,
    es6: true,
    jest: true,
  },
  extends: [
    'airbnb-base',
    'plugin:jest/all',
  ],
  globals: {
    Atomics: 'readonly',
    SharedArrayBuffer: 'readonly',
  },
  parserOptions: {
    ecmaVersion: 2018,
    sourceType: 'module',
  },
  plugins: ['jest'],
  rules: {
    'no-console': 'off',
    'no-shadow': 'off',
    'no-restricted-syntax': [
      'error',
      'LabeledStatement',
      'WithStatement',
    ],
  },
  overrides:[
    {
      files: ['*.js'],
      excludedFiles: 'babel.config.js',
    }
  ]
};

```
