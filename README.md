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
    "src/**/*.ts?x",
    "test?s/**/*.ts?x",
    "**/*.json",
    "*.d.ts",
    "src/*.d.ts"
  ]
}
```

```json
{
  "extends": "some-tsconfig-preset/workers",
  "include": [
    "src/**/*.ts?x",
    "test?s/**/*.ts?x",
    "**/*.json",
    "*.d.ts",
    "src/*.d.ts"
  ]
}
```
