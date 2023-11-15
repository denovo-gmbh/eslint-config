#  @denovo/eslint-config

A [ESLint](https://eslint.org) [configuration](https://eslint.org/docs/latest/use/getting-started)
for projects following the [Denovo](https://denovo.at/) coding guidelines.

## Installation

```
npm install --save-dev @denovo/eslint-config
```

## Usage

Specify `eslintConfig` property in `package.json`:

```json
{
  "name": "another-project",
  "eslintConfig": {
    "extends": "@denovo/eslint-config"
  },
  "devDependencies" : {
    "@denovo/eslint-config": "^1.0.0"
  }
}
```

## How to contribute

 - Change the `index.js` file in arrangement with the Denovo QA team.
 - Run `npm run publish` and follow the instructions.
