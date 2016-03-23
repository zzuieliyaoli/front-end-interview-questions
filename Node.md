# Node

## Path

There is a directory shown below:

```shell
app/
    -lib/
        -common.js
    -model
        -task.js
        -test.js
```

and `task.js`

```javascript
var path = require('path');

console.log(__dirname);
console.log(__filename);
console.log(process.cwd());
console.log(path.resolve('./'));
```

Questions:

1. What's the output when we run `node task.js` in the `model` directory?
2. What's the output when we run `node model/task.js` in the `app` directory?


Hint: [浅析 NodeJs 的几种文件路径](https://github.com/imsobear/blog/issues/48)
