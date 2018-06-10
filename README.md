# vika
A boilerplate for starting web applications with Express 4 and Pug

## What's inisde:
*A server side setup very similar to the result of express-generator...* 
- Express
- Pug
- body-parser, cookie-parser
- morgan, debug
- serve-favicon with default [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) favicon.ico in place

*Dev dependencies to prepare client side JavaScript...*
- broweserify
- babel-core, babel-preset-env, babelify
- uglify-js

*This command will transpile `client/client.js` to `public/js/client.min.js`...*

`npm run build` 

## Preflight Checklist
* You should...
- Change the title of your application in `/routes/index.js`
- Give your project a `name` and `version` in `package.json`
- Build the best app ever!
