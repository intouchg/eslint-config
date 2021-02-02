# @i/eslint-config

ESLint configuration for the Intouch Design System


### Getting Started

This ESLint configuration is automatically included in the Intouch Design System app boilerplate [@i/starter](https://intazdoweb.intouchsol.com/IntouchDesignSystem/IntouchDesignSystem/_git/starter).

To use in your own custom configuration, install then extend this package in your eslint config:

```jsonc
// package.json
{
    "devDependencies": {
        "@i/eslint-config": "latest",
        "@typescript-eslint/eslint-plugin": "^3.10.1",
        "@typescript-eslint/parser": "^3.10.1",
        "babel-eslint": "^10.1.0",
        "eslint": "^7.7.0",
        "eslint-plugin-react": "^7.20.6",
        "eslint-plugin-react-hooks": "^4.1.0",
        "typescript": "^3.9.7"
    }
}
```
<br>

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