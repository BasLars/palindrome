# Phrase object (with palindrome detector)

This is a sample NPM module by Michael Hartl

The module can be used as follows:

```
$ npm install --global baslars-palindrome
$ vim test.js
let Phrase = require("baslars-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```