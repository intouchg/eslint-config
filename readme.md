# @intouchg/eslint-config

ESLint configuration for the [Intouch Design System](https://ids.intouchg.co/)

## Getting Started

This ESLint configuration is automatically included in the Intouch Design System app boilerplate [@intouchg/starter](https://npmjs.com/package/@intouchg/starter).

To use in your own custom configuration, install then extend this package in your ESLint config:

1. Install dependencies
```sh
yarn add @intouchg/eslint-config @babel/eslint-parser @babel/eslint-plugin @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-prettier eslint-plugin-react eslint-plugin-react-hooks typescript 
```
Note: Due to the way ESLint `overrides` work, Typescript `devDependencies` are required regardless of whether you are using Typescript in your project.

2. Configure ESLint
```jsonc
// .eslintrc
{
    "extends": ["@intouchg/eslint-config"]
}
```
