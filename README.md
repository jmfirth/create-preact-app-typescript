# `preact-scripts-ts` [![npm version](https://badge.fury.io/js/preact-scripts-ts.svg)](https://badge.fury.io/js/preact-scripts-ts)

Create Preact apps (with Typescript) with no build configuration.

Compressed output:

```
File sizes after gzip:

  8.42 KB  build/static/js/main.c57e6d2d.js
  289 B    build/static/css/main.9a0fe4f1.css
```

## tl;dr

```sh
npm install -g create-react-app

create-react-app my-app --scripts-version=preact-scripts-ts
cd my-app/
npm start
```

## Additional Features

**Code highlighting on error**

When you run `npm run build` the terminal will output the error, including the highlighted sourecode (like babel)!

![CodeHighlight](https://cloud.githubusercontent.com/assets/175278/22310149/1ee66ccc-e346-11e6-83ff-e3a053701fb4.gif)

## Credits

Forked from [react-scripts-ts](https://github.com/wmonk/create-react-app-typescript) by William Monk.