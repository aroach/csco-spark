# Cisco Spark API Integration

##### Usage

```javascript
var sparkFactory = require('spark'),

var spark = sparkFactory({
  uri: 'spark api url',
  token: 'bearer token'
});

spark.sendMessage({roomId:'room', text: 'message'}).then(function(res) {
  //Store the res data?
});
```
