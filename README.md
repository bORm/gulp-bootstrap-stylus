# gulp-bootstrap-stylus

## Use

Javascript - add just like you'd use nib:

```javascript
var bootstrap = require('bootstrap-stylus'),
       stylus = require('stylus');

.pipe stylus(
    'include css': true
    use: [bootstrap()]
)
```

in your .styl files:

```styl
@import bootstrap
````
