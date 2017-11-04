# Setup
You will need:
* `dist/cubic-api-controls.js`
* `dist/cubic.js`
* `dist/cubic-custom-fns.js`
* `dist/objects.json`
## Scripting
In `dist/cubic-api-controls.js`, type:
```javascript
  var options;
  var imports = ["node.js", "cubic-*.js", "cubic.js"];
  function init(configType){
    options = {
      _config: configType,
      _array: null
    };
  }
```
