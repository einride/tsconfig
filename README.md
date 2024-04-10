# @einride/tsconfig

[![license](https://img.shields.io/npm/l/@einride/tsconfig.svg)](https://github.com/einride/tsconfig/blob/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/@einride/tsconfig.svg)](https://www.npmjs.com/package/@einride/tsconfig)
[![total npm downloads](https://img.shields.io/npm/dt/@einride/tsconfig.svg)](https://www.npmjs.com/package/@einride/tsconfig)

Einride's default TSconfig.

## Installation

Install `@einride/tsconfig` as a dev dependency.

```bash
yarn add @einride/tsconfig --dev
```

## Usage

Register the config in your `tsconfig.json`:

```json
{
  "extends": "@einride/tsconfig"
}
```

You can add additional options in your project, which will override the option in
`@einride/tsconfig` if it's defined there.

```json
{
  "extends": "@einride/tsconfig",
  "compilerOptions": {
    "baseUrl": "./src"
  }
}
```

## Contribute

See [Contributing Guide](https://github.com/einride/tsconfig/blob/master/CONTRIBUTING.md).

## License

MIT
