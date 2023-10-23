# some-tsconfig-preset

> A preset for tsconfig.json

## Install

```sh
npm install -D some-tsconfig-preset
```

or
  
  ```sh
pnpm add -D some-tsconfig-preset
```

## Usage

tsconfig.json:

```json
{
  "extends": "some-tsconfig-preset",
  "include": [
    "src/**/*",
    "test?s/**/*.ts?x",
    "**/*.json",
    "*.d.ts"
  ]
}
```

```json
{
  "extends": "some-tsconfig-preset/workers",
  "include": [
    "src/**/*",
    "test?s/**/*.ts?x",
    "**/*.json",
    "*.d.ts"
  ]
}
```

```json
{
  "extends": "some-tsconfig-preset/node",
  "include": [
    "src/**/*",
    "scripts/**/*.ts?x",
    "test?s/**/*.ts?x",
    "**/*.json",
    "*.d.ts"
  ]
}
```

Additionally, you can add `some-tsconfig-preset/strict` to forbid unused variables and parameters.
