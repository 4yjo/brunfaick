# brainfuck-interpreter

> A Brainfuck interpreter implemented in JavaScript.


## Install

```
$ npm install --save brainfuck-interpreter
```


## Usage

```js
const brainfuck = require('brainfuck-interpreter');

brainfuck('++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.');
//=> 'Hello World!'
```


## API

### brainfuck(program, input)

#### program

Type: `string`

A string of Brainfuck commands.

#### input

Type: `string`<br>
Default: `undefined`

Input provided to `program` during execution.



## CLI

```
$ npm install --global brainfuck-interpreter
```

```
$ brainfuck-interpreter --help
  Usage
    $ brainfuck-interpeter [program]

  Options
    -i, --input
      Input provided to [program] during execution.

  Examples
    $ brainfuck-interpreter ++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.
      Hello World!
```


## License

MIT © [Max Hallinan](https://github.com/maxhallinan)
