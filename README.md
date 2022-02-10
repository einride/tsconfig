# @einride/tsconfig

[![license](https://img.shields.io/npm/l/@einride/tsconfig.svg)](https://github.com/einride/tsconfig/blob/main/LICENSE)
[![npm version](https://img.shields.io/npm/v/@einride/tsconfig.svg)](https://www.npmjs.com/package/@einride/tsconfig)
[![total npm downloads](https://img.shields.io/npm/dt/@einride/tsconfig.svg)](https://www.npmjs.com/package/@einride/tsconfig)

Einride's default TSconfig.

## Installation

Install this package as a dev dependency.

```bash
# npm
npm install @einride/tsconfig --save-dev

# yarn
yarn add @einride/tsconfig --dev
```

## Usage

Register the config in your `tsconfig.json`:

```json
{
  "extends": "@einride/tsconfig/tsconfig.json"
}
```

You can add additional options in your project, which will override the option
in `@einride/tsconfig` if it's defined there.

```json
{
  "extends": "@einride/tsconfig/tsconfig.json",
  "compilerOptions": {
    "strict": false,
    "baseUrl": "src"
  }
}
```

## License

MIT
