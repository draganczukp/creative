# p5-ts-starter
A simple starter project for p5 and typescript

# Usage
```
git clone https://github.com/draganczukp/p5-ts-starter
```
Or use the new "Use this template" feature on GitHub, then

```sh
cd p5-ts-starter
yarn install
```

You can run a dev server using
```
yarn run dev
```
The server watches for changes and compiles typescript (and sass if you have any) and reloads your
browser automatically.

# Folder structure
```sh
.
├── dist
│   ├── bundle.js # All ts files compiled into one
│   ├── bundle.js.map # source map
│   └── css
│       ├── style.css # All scss files compiled into one
│       └── style.css.map # source map
├── global.d.ts # p5 global mode definitions
├── index.html
├── package.json
├── readme.md
├── src # Put all your source files here
│   ├── scss
│   │   └── style.scss
│   └── ts # All .ts files from here will be compiled into single .js file
│       └── sketch.ts
├── tsconfig.json
└── yarn.lock
```
