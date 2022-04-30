# Beland ESLint & Prettier Config

## Installation
```sh
npm install -D @beland/eslint-config
```

## Usage

In `eslintrc.json`:

```js
{
  "extends": "@beland/eslint-config",
  "parserOptions": {
    "project": ["tsconfig.json", "test/tsconfig.json"]
  }
}
```


## License

Apache 2.0
