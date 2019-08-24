# mbr-prompt

Simple password prompt for NodeJS process. No symbols are being displayed while typing.

```
const prompt = require('mbr-prompt');

prompt('Please enter your password', function (password) {
  console.log('Entered password is:', password);
});
```

First argument is user-readable string - password input invitation.

Second argument is a callback, which receives user input value as an argument after Enter was pressed.
