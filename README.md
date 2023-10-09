# Cypress Typescript Boilerplate

## What is it?

A cypress boilerplate using TS, ESLint and Husky hooks for commitizen git messages standardization.

## Usage

First, install the dependencies using yarn

```sh
$ yarn install
```

Husky hooks will be installed at the end of the install script.

For testing development, the following cypress scripts can be used:
```sh
# Lints whole project according to eslint config
yarn lint 

# Run cypress on GUI mode
yarn cypress:open 

# Run cypress on CLI mode
yarn cypress:run
```

## References
- [Cypress Documentation for Typescript](https://docs.cypress.io/guides/tooling/typescript-support)
- [Cypress IDE Integration](https://docs.cypress.io/guides/tooling/IDE-integration)
- [Commitizen (Making your repo commitizen friendly)](https://github.com/commitizen/cz-cli?tab=readme-ov-file#making-your-repo-commitizen-friendly)
- [Husky (Getting started)](https://typicode.github.io/husky/getting-started.html)
