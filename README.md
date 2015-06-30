node-random-port
================

get a free random tcp port and pass to the callback


```javascript
var random_port = require('random-port');

random_port(callback); // default will return a port from 15000 to 15099

random_port({from: 20000}, callback);

random_port({from: 20000, range: 10}, callback);
```
