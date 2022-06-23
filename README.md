# Unique ID generator

*You can specify the length of the ID. The default (without specifying) is 10 characters.*

**Available sign:** ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789!@#$%^&*()?

**Example 01:**
```
const randomID = require('@tycjann/randomid-generator');
console.log(randomID());
```
**Example 02:**
```
const randomID = require('@tycjann/randomid-generator');
console.log(randomID(30));
```