# `@xunmi/prettier-config`

> My personal [Prettier](https://prettier.io) config.

## Install

```bash
npm install -D @xunmi/prettier-config
```

## Usage

- edit `package.json`:

  ```json
  {
    "prettier": "@xunmi/prettier-config"
  }
  ```

- or edit the configuration file, e.g. `.prettierrc.js`:

  ```js
  module.exports = {
    ...require('@xunmi/prettier-config'),
    semi: false,
  };
  ```

## Notes

- `trailingComma`

   value: **`es5`**
   
   default value changed from `none` to `es5` in v2.0.0
   
- `arrowParens`

   value: **`avoid`**

   default value changed from `avoid` to `always` in v2.0.0
   
- `endOfLine`

   value: **`lf`**

   default value changed from `auto` to `lf` in v2.0.0
