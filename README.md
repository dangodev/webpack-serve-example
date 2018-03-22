# webpack-serve bug repro

### Instructions
1. Run `yarn`
2. Run `yarn start`

See the following error:

```
module.js:545
    throw err;
    ^

Error: Cannot find module './lib/HotClientError'
    at Function.Module._resolveFilename (module.js:543:15)
    at Function.Module._load (module.js:470:25)
    at Module.require (module.js:593:17)
    at require (/Users/drew/Sites/webpack-serve/node_modules/v8-compile-cache/v8-compile-cache.js:159:20)
    at Object.<anonymous> (/Users/drew/Sites/webpack-serve/node_modules/webpack-hot-client/index.js:5:24)
    at Module._compile (/Users/drew/Sites/webpack-serve/node_modules/v8-compile-cache/v8-compile-cache.js:178:30)
    at Object.Module._extensions..js (module.js:660:10)
    at Module.load (module.js:561:32)
    at tryModuleLoad (module.js:501:12)
    at Function.Module._load (module.js:493:3)
error An unexpected error occurred: "Command failed.
```
