# template-typescript-mono-repo

Heavily inspired by https://github.com/andrewthauer/ts-monorepo

## Goals

- Seperate concerns into packages like `web`, `server`, `mobile`
- Allow for TypeScript to tooling to work (IDE go to)
- Make deployment easy
- Centerlized testing with `jest` and linting/formatting with `eslint` and `prettier`

## How it works

Steps:

1. Install deps with lerna using `yarn install` then `yarn bootstrap`
2. Build TypeScript Packages
