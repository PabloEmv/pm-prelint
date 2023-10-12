# pm-prelint

**pm-prelint** is a package that provides ESLint and Prettier configuration for React and TypeScript projects.

## Installation

You can install **pm-prelint** using npm:

    npm install pm-prelint --save-dev

## Configuration

### ESLint

To use the ESLint configuration from **pm-prelint** in your project, add the following to your `.eslintrc.cjs` file:

    const { eslint } = require('pm-prelint/index')
    
    module.exports = {
    extends: [eslint]
    }
### Prettier

To use the Prettier configuration from **pm-prelint** in your project, add the following to your `.prettierrc.cjs` file:

    const { prettier } = require('pm-prelint/index.js')
    module.exports = prettier

## #Author

Pablo Martínez: [PabloEmv (github.com)](https://github.com/PabloEmv)