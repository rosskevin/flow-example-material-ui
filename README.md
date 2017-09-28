# flow-example-material-ui

[![CircleCI](https://circleci.com/gh/rosskevin/flow-example-material-ui/tree/master.svg?style=svg&circle-token=9de60bf76b13f269bb560cd89ea253c9c04238ce)](https://circleci.com/gh/rosskevin/flow-example-material-ui/tree/master)

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