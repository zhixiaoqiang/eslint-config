# @jzone/eslint-config

> An ESLint Shareable Config 

## Install

```bash
# npm
npm install @jzone/eslint-config -D

# yarn
yarn add @jzone/eslint-config -D
```

## Webpack Usage

```js
// .eslintrc.js
module.exports = {
  extends: ['@jzone/eslint-config'],
}
```

```js
// .eslintignore
# Ignore files

node_modules/*
build/*
```

## Introduction

1. use `babel-eslint` parser
2. extends `eslint-config-standard` and `eslint-config-standard-jsx`
3. add `react-hooks` plugin
4. other...
