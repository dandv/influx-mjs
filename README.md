Run `yarn` then `node -r babel-register index.js`. The script should output `1`.

Now run `node -exprimental-modules index.mjs`. Node fails with the error

```
SyntaxError: The requested module does not provide an export named 'FieldType'
    at checkComplete (internal/loader/ModuleJob.js:75:27)
    at moduleJob.linked.then (internal/loader/ModuleJob.js:58:11)
    at <anonymous>
```
