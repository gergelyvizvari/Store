# FV Store

This package is on hold
Fast and simple key = value storage

### Usage

```js
import Store from "fv-store";

Store.set({
    user: {
        firstName: 'Gergely',
        lastName: 'Vizvari'
    }
});

console.log(Store.get('user.firstName', 'defaultValue'));
```
