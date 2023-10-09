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