# loadXML - Auth

A function for loading external JSON files with callback methods

## Example

```
var auth = authentication("user","password");

loadJSONAuth("./src/script/data.json", function(response) {

  var data = JSON.parse(response);

  console.log(data);

}, auth);
```