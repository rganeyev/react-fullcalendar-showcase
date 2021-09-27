# Fullcalendar: react + sass = 😥

I removed everything, but included index.scss to the build with the following:

```
@import '@fullcalendar/common/main.css';
```

React starts well in development:

```
yarn start
```

But fails on build:
```
yarn build
yarn run v1.22.5
$ react-scripts build
Creating an optimized production build...
Browserslist: caniuse-lite is outdated. Please run:
npx browserslist@latest --update-db

Why you should do it regularly:
https://github.com/browserslist/browserslist#browsers-data-updating
Failed to compile.

./src/index.scss
ParserError: Syntax Error at line: 1, column 45


error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.   
```
