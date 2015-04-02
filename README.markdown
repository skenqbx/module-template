# module-template

**_A template for node/io.js modules_**

```
Stability: 1 - Experimental
```

**basics**

 - `.eslintrc` & `.eslintignore` - style rules closely follow google's javascript style guide
 - `.gitignore` & `.npmignore`
 - MIT [LICENSE](./LICENSE)
 - a `index.js` pointing to `lib/`
 - plus a `.travis.yml`

**package.json scripts**

 - `npm test` - eslint + istanbul + mocha
 - `npm run lint` - eslint
 - `npm run update` - next-update
 - `npm run clean` - rm `coverage/`, `node_modules`, `npm-debug.log`

[**Download**](https://github.com/skenqbx/module-template/archive/master.zip)

## Tests

```bash
npm test
firefox coverage/lcov-report/index.html
```

### Coverage

```
Statements   : XX.XX% ( YY/ZZ )
Branches     : XX.XX% ( YY/ZZ )
Functions    : XX.XX% ( YY/ZZ )
Lines        : XX.XX% ( YY/ZZ )
```
