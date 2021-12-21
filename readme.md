# @intouchg/eslint-config

ESLint configuration for the [Intouch Design System](https://ids.intouchg.co/)


## Getting Started

This ESLint configuration is automatically included in the Intouch Design System app boilerplate [@intouchg/starter](https://npmjs.com/package/@intouchg/starter).

To use in your own custom configuration, install then extend this package in your eslint config.

### Install dependencies

```jsonc
// package.json
{
    "devDependencies": {
        "@babel/eslint-parser": "7.16.5",
        "@babel/eslint-plugin": "7.16.5",
        "@typescript-eslint/eslint-plugin": "5.8.0",
        "@typescript-eslint/parser": "5.8.0",
        "eslint": "8.5.0",
        "eslint-config-prettier": "8.3.0",
        "eslint-plugin-react": "7.27.1",
        "eslint-plugin-react-hooks": "4.3.0",
        "typescript": "4.5.4"
    }
}
```
Note: Due to the way ESLint `overrides` work, Typescript `devDependencies` are required regardless of whether you are using Typescript in your project.

### Configure eslint

```jsonc
// .eslintrc
{
    "extends": [
        "@intouchg/eslint-config"
    ]
}
```

or

```js
// .eslintrc.js
module.exports = {
    extends: [ require.resolve('@intouchg/eslint-config') ],
}
```