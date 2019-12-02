# `@jzone/eslint-config`

> An ESLint Shareable Config 

## Usage

```bash
yarn add @jzone/eslint-config -D
```

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
