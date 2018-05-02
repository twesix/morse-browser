#morse-browser

A simple Morse code library for browser

![Samuel F.B. Morse](avatar.jpg)

## install

```bash
npm install morse-browser
```

## example usage

First, include the morse.js in your html

```html
<script src="morse.js"></script>
```

Then, use morse.encode to encode and morse.decode for decode

```javascript

const encoded = morse.encode('Hello, world.');
// ...././.-../.-../---/--..--/......./.--/---/.-./.-../-../.-.-.-

morse.decode(encoded);
// HELLO, WORLD.
```

```javascript
const encoded = morse.encode([ 'hello', 'world' ]);
// ["...././.-../.-../---", ".--/---/.-./.-../-.."]

morse.decode(encoded);
// [ 'HELLO', 'WORLD' ]
```

## methods

### morse.encode(obj)

Encodes and returns a given string or array

### morse.decode(obj)

Decodes and returns a string or array


## license

MIT
