# CAINode
Unofficial Character.AI API using Node JS
# Install
`npm install cainode`
# Example
```js
const CAINode = require("./index.js");
const Char_AI = new CAINode();

(async function() {
    await Char_AI.login("Your Character AI Token");
    console.log("Login successfully");
    await Char_AI.logout()
})();
```
