# flow-example-material-ui

[![CircleCI](https://circleci.com/gh/rosskevin/flow-example-material-ui/tree/master.svg?style=svg&circle-token=5f5e59c1541acc06d6e3cb249f6e7b1a3c84f146)](https://circleci.com/gh/rosskevin/flow-example-material-ui/tree/master)

## Note
This code is included in `material-ui/examples/create-react-app-with-flow`.  It's only here as a canary to make sure everyting builds.

## How to use

- `yarn` to install dependencies
- `yarn flow`

## From scratch setup

- copy `.flowconfig`
- change `module.name_mapper` to your project name
- copy `flow` dir
- `yarn add -D flow-bin`
- decide on `enzyme` - flow is expecting it in your `package.json` because `material-ui` includes reusable `test-utils`.  If you do not want it, uncomment `L12` in the `.flowconfig` 
- copy `package.json` script `flow`
- `flow-typed install`
- `yarn flow`

## Problems?

- Please submit a PR with the fixes so this sample can stay up to date.
- Please do not email me/contact me as your personal development support.