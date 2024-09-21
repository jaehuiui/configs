# @jaehuiui/eslint-config

## Usage

```js
// .eslintrc.js
require('@jaehuiui/eslint-config/patch')

module.exports = {
  extends: ['@jaehuiui/eslint-config'], // ['@jaehuiui/eslint-config/react']
  parserOptions: {
    project: './tsconfig.json',
    tsconfigRootDir: __dirname,
  },
  settings: {
    'import/resolver': {
      typescript: {
        project: './tsconfig.json',
      },
    },
  },
}
```