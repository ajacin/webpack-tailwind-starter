# webpack-tailwind-starter

A base repository to build applications with webpack and to use tailwind css

## npm init -y

## install tailwind

npm i -D tailwindcss

npm i -D webpack webpack-cli webpack-dev-server style-loader css-loader postcss postcss-loader postcss-preset-env
Added webpack config
npm run build should create a dist folder

If the below are not specified,

npm run build creates a main.js

```js
entry: "./src/index.js",
  output: {
    path: path.resolve(__dirname, "dist"),
    filename: "bundle.js",
  },
```

npx tailiwind init

add tailwind as postcss
