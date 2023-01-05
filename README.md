<div align="center">
  <h1>@autosoft/eslint-config</h1>
  <a href="https://npmjs.com/package/autosoft/eslint-config">
    <img alt="npm" src="https://img.shields.io/npm/v/@autosoft/eslint-config.svg">
  </a>
  <a href="https://github.com/autosoftoss/eslint-config">
    <img alt="typescript" src="https://img.shields.io/github/languages/top/autosoftoss/eslint-config.svg">
  </a>
</div>

<br />

<blockquote align="center">A base for projects that use ESLint.</blockquote>

_If I should maintain this repo, please ⭐️_
<a href="https://github.com/autosoftoss/eslint-config">
  <img align="right" alt="GitHub stars" src="https://img.shields.io/github/stars/autosoftoss/eslint-config?label=%E2%AD%90%EF%B8%8F&style=social">
</a>

_DM me on [Twitter](https://twitter.com/bconnorwhite) if you have questions or suggestions._
<a href="https://twitter.com/bconnorwhite">
  <img align="right" alt="Twitter Follow" src="https://img.shields.io/twitter/url?label=%40bconnorwhite&style=social&url=https%3A%2F%2Ftwitter.com%2Fbconnorwhite">
</a>

---

## Installation

```sh
yarn add --dev @autosoft/eslint-config
```

```sh
npm install --save-dev @autosoft/eslint-config
```

```sh
pnpm add --save-dev @autosoft/eslint-config
```

## Usage

In your `package.json` file:

```json
{
  "eslintConfig": {
    "extends": "@autosoft/eslint-config"
  }
}
```

### ESLint

Now to run ESLint, run `yarn eslint source` or `npm run eslint source`.

<br />

<h2 id="dependencies">Dependencies<a href="https://www.npmjs.com/package/autosoft/eslint-config?activeTab=dependencies"><img align="right" alt="dependencies" src="https://img.shields.io/librariesio/release/npm/@autosoft/eslint-config.svg"></a></h2>

- [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin): TypeScript plugin for ESLint
- [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser): An ESLint custom parser which leverages TypeScript ESTree
- [eslint](https://www.npmjs.com/package/eslint): An AST-based pattern checker for JavaScript.
- [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import): Import with sanity.
- [eslint-plugin-json](https://www.npmjs.com/package/eslint-plugin-json): Eslint plugin for JSON files
- [eslint-plugin-react](https://www.npmjs.com/package/eslint-plugin-react): React specific linting rules for ESLint
- [eslint-plugin-react-hooks](https://www.npmjs.com/package/eslint-plugin-react-hooks): ESLint rules for React Hooks
- [types-eslintrc](https://www.npmjs.com/package/types-eslintrc): Type checking for .eslintrc.json

<h3 id="dev-dependencies">Dev Dependencies</h3>

- [@autosoft/tsconfig](https://www.npmjs.com/package/@autosoft/tsconfig): A base for TypeScript projects.


<br />


<h2 id="license">License <a href="https://opensource.org/licenses/MIT"><img align="right" alt="license" src="https://img.shields.io/npm/l/@autosoft/eslint-config.svg"></a></h2>

[MIT](https://opensource.org/licenses/MIT)
