# ES6 Basics

This project focuses on understanding and implementing ES6 features in JavaScript. It is part of the short specializations curriculum.

## Concepts Covered
- Modern JavaScript
- Software Linter

## Learning Objectives
By the end of this project, participants should be able to explain:
- What ES6 is and its new features.
- Differences between constants and variables.
- Block-scoped variables.
- Arrow functions and default function parameters.
- Usage of rest and spread function parameters.
- String templating, object creation, and properties in ES6.
- Iterators and for-of loops.

## Requirements
- All files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x.
- Allowed editors: vi, vim, emacs, Visual Studio Code.
- All files should end with a new line.
- A `README.md` file is mandatory.
- Your code should use the `.js` extension and will be tested using Jest and ESLint.

## Setup Instructions

1. **Install NodeJS 12.11.x**: Run the following commands in your home directory:
   ```sh
   curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
   sudo bash nodesource_setup.sh
   sudo apt install nodejs -y
   ```

2. **Install Jest, Babel, and ESLint**: In your project directory, use the supplied `package.json` and run:
   ```sh
   npm install
   ```

3. **Configuration Files**: Ensure the following files are in your project directory:
   - `package.json`
   - `babel.config.js`
   - `.eslintrc.js`

4. **Run npm install**: Ensure all project dependencies are installed by running:
   ```sh
   npm install
   ```

## Tasks

### 0. Const or let?
- Modify `taskFirst` and `taskNext` functions to use `const` and `let`.

### 1. Block Scope
- Update `taskBlock` to prevent variable overwrites inside the conditional block.

### 2. Arrow Functions
- Convert a standard function to use ES6’s arrow syntax.

...

## Resources
- [ECMAScript 6 - ECMAScript 2015](https://www.ecma-international.org/ecma-262/6.0/)
- [Statements and Declarations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements)
- [Arrow Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
- [Default Parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)
- [Rest Parameter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
- [JavaScript ES6 — Iterables and Iterators](https://medium.com/siliconwat/javascript-es6-the-iterables-and-iterators-cc840d799f1c)

## Final Notes
- Don’t forget to run `npm install` from your project folder to install all necessary dependencies.

---

© 2024 ALX. All rights reserved.