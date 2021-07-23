# Disboard tampermonkey template script

A simple template project to develop a tampermonkey script

# Instructions

- First run on the terminal

```sh
npm install
```

## For development

- Run on the terminal

```sh
npm run dev
```

- Create a tampermonkey script containing ([file](devTamperMonkeyScript.js)):

```js
// ==UserScript==
// @name        Dev loader
// @namespace   devdevdevdev
// @description Dev loader
// @include     *
// @version     1
// @require     http://localhost:1234/index.js
//              or whatever url the parcel server is running at
// ==/UserScript==
```

## For building the script

```sh
npm run build
```

And just copy everything in the script and paste it in a new tampermonkey script,
remember to replace the `// @match` on the tampermonkey script
