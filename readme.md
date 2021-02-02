# @i/eslint-config

ESLint configuration for the Intouch Design System


### Getting Started

This ESLint configuration is automatically included in the Intouch Design System app boilerplate [@i/starter](https://intazdoweb.intouchsol.com/IntouchDesignSystem/IntouchDesignSystem/_git/starter).

To use in your own custom configuration, install then extend this package in your eslint config.


#### Install dependencies

Dependencies to lint JavaScript:
```jsonc
// package.json
{
    "devDependencies": {
        "@babel/eslint-parser": "7.12.1",
        "@babel/eslint-plugin": "7.11.5",
        "@i/eslint-config": "latest",
        "eslint": "7.19.0",
        "eslint-plugin-react": "7.22.0",
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
        "@babel/eslint-parser": "7.12.1",
        "@babel/eslint-plugin": "7.11.5",
        "@i/eslint-config": "latest",
        "@typescript-eslint/eslint-plugin": "4.14.2",
        "@typescript-eslint/parser": "4.14.2",
        "eslint": "7.19.0",
        "eslint-plugin-react": "7.22.0",
        "eslint-plugin-react-hooks": "4.2.0",
        "typescript": "4.1.3"
    }
}
```


#### Configure eslint

```jsonc
// .eslintrc
{
    "extends": [
        "@i/eslint-config"
    ]
}
```

or

```js
// .eslintrc.js
module.exports = {
    extends: [ require.resolve('@i/eslint-config') ],
}
```