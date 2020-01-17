# Cross uuid
The cross environment uuid generator that works in node and browser environment

# Install
```bash
    npm install cross-uuid
```
# How to use
##NodeJS
```javascript
    const UUID = require('cross-uuid');
    const uuid = UUID.generate();  
```
##Browser
```javascript
    import UUID from '/node_modules/cross-uuid/browser/main.js';
   const uuid = UUID.generate();
```