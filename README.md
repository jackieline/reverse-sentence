# reverse-sentence
Reverses the words of a sentence.
## Install
```sh
npm install @npmusername/reverse-sentence
```
## API
```js
require("reverse-sentence") => Function
reverse(sentence) => String
```
## Example
```js
const reverseSentence = require("reverse-sentence");
const sentence = "Hello Jackie!";
const reversed = reverseSentence(sentence);
console.log(reversed) // Jackie! Hello
```
## License
MIT