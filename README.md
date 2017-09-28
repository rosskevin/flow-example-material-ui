# flow-example-material-ui

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