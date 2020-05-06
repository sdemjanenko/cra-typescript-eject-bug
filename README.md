Demonstrates a bug with ejecting from [Create React App](https://github.com/facebook/create-react-app).

Run
`yarn install`
`yarn run eject`

Look for Jest's `modulePaths` in `package.json`. It will reference an absolute
path instead of a path relative to `<rootDir>`.
