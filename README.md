# @einride/tsconfig

[![license](https://img.shields.io/npm/l/@einride/tsconfig.svg)](https://github.com/einride/eslint-plugin/blob/main/LICENSE)
[![npm version](https://img.shields.io/npm/v/@einride/tsconfig.svg)](https://www.npmjs.com/package/@einride/eslint-plugin)
[![total npm downloads](https://img.shields.io/npm/dt/@einride/tsconfig.svg)](https://www.npmjs.com/package/@einride/eslint-plugin)

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
"extends": "@einride/tsconfig"
```

You can override specific options if you have a need for that in your project:

```json
{
  "extends": "@einride/tsconfig",
  "compilerOptions": {
    "strict": false
  }
}
```

## License

MIT
