# eslint-checker

[![NPM version](https://badge.fury.io/js/eslint-checker.svg)](https://www.npmjs.com/package/eslint-checker)
[![Downloads](http://img.shields.io/npm/dm/eslint-checker.svg)](https://npmjs.org/package/eslint-checker)
[![](https://img.shields.io/npm/l/eslint-checker.svg)](https://img.shields.io/npm/l/eslint-checker.svg)


eslint-checker is the module to synchronize linting rules in the distributed development environment.

- Works on the latest [eslint](https://eslint.org/docs/rules/) rules
- Serves linting rules for Typescript, React (tsx support) and Nodejs projects
- Easily extensible
- Easy incorporation

## Usage

The package can be integrated very easily in any project.

```
 - npm i @amittksharma/eslint-checker --save
```

Create a `eslint.json` file in the root folder of your project and add
the following:

```json
{
  "extends": "eslint-checker/eslint"
}
```

### Incorporation for React projects (.tsx files)

```json
{
  "extends": "eslint-checker/react.eslint"
}
```

## Reference Linting Rules:

[Eslint Rules](https://eslint.org/docs/developer-guide/shareable-configs)

## License

MIT
