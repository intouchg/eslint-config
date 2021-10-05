# @intouchg/eslint-config

ESLint configuration for the Intouch Design System


### Getting Started

This ESLint configuration is automatically included in the Intouch Design System app boilerplate [@intouchg/starter](https://npmjs.com/package/@intouchg/starter).

To use in your own custom configuration, install then extend this package in your eslint config.


#### Install dependencies

Dependencies to lint JavaScript:
```jsonc
// package.json
{
    "devDependencies": {
        "@babel/eslint-parser": "7.14.7",
        "@babel/eslint-plugin": "7.14.5",
        "@intouchg/eslint-config": "latest",
        "eslint": "7.30.0",
        "eslint-config-prettier": "8.3.0",
        "eslint-plugin-react": "7.24.0",
        "eslint-plugin-react-hooks": "4.2.0",
    }
}
```
<br>

or

Dependencies to link JavaScript and TypeScript:
```jsonc
// package.json
{
    "devDependencies": {
        "@babel/eslint-parser": "7.14.7",
        "@babel/eslint-plugin": "7.14.5",
        "@intouchg/eslint-config": "latest",
        "@typescript-eslint/eslint-plugin": "4.28.3",
        "@typescript-eslint/parser": "4.28.3",
        "eslint": "7.30.0",
        "eslint-config-prettier": "8.3.0",
        "eslint-plugin-react": "7.24.0",
        "eslint-plugin-react-hooks": "4.2.0",
        "typescript": "4.3.5"
    }
}
```


#### Configure eslint

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