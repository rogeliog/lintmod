# Work in progress, not ready

Make sure to look at [cpojer/js-codemod](https://github.com/cpojer/js-codemod) for a well maintained codemod collection :)

## Setup

```
npm install -g jscodeshift
git clone https://github.com/rogeliog/lintmod
jscodeshift -t <codemod-script> <file>
```
##### Usage

`jscodeshift -t transforms/no-console/transform.js path/to/foo/`
