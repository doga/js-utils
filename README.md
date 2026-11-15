# js-utils

Utility functions for javascript.

## How to use

```javascript
import {
  isNull, isUndefined, isArray, isPlainObject, isString, isEmptyString, isEmptyArray, isBoolean
} from 'https://cdn.jsdelivr.net/gh/doga/js-utils@1.0.0/mod.mjs';

isPlainObject({});      // true
isArray([]);            // true
isEmptyArray([]);       // true
isString('');           // true
isEmptyString('');      // true
isBoolean(false);       // true
isNull(null);           // true
isUndefined(undefined); // true
```

∎
