# Morse
A Morse encoder and decoder

### Example Usage
```javascript
let encode="Hello, World!";
encode=encodeString(encode);
let decode=".... . -.-- / -. --- .-- -.-.--";
decode=decodeString(decode);
console.log(encode,'\n',decode);
```
#### Output
.... . .-.. .-.. --- --..-- / .-- --- .-. .-.. -.. -.-.-- /  
 HEY NOW!
