# vite-bug-1

To reproduce:
`$ npm i`
`$ npm run dev`

Then go to the browser http://localhost:3000.

See error in Console:

```
Uncaught TypeError: Cannot read property '__moduleExports' of undefined
    at use-http.js:1411
    at createCommonjsModule (use-http.js:16)
    at use-http.js:1391
```
