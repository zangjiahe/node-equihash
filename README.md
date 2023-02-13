

# 示例
````javascript
var ev = require('bindings')('equihashverify.node');

var header = new Buffer(..., 'hex');
var solution = new Buffer(..., 'hex'); //do not include byte size preamble "fd4005"

ev.verify(header, solution, n, k);
//returns boolean
````

# 默认 （200,9）
````javascript
ev.verify(header, solution);
````


