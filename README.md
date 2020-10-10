# Tic-Tac-Nano 2
Tic-Tac-Nano 2 is a tic tac toe class that is simple and easy to use

## Installation
To install this package, you need the [node package manage](http://npmjs.org)
```bash
npm install tic-tac-nano-2
```

## Usage
Tic-Tac-Nano 2 is quite simple to use. To initalize a tic tac toe game, call the class:
```js
const ticTacNano = require('tic-tac-nano-2');

const a = new ticTacNano('X', 'O')
```

With initialization, the class has many neat functions, such as:

```js
a.turn(/*Board spot*/,"A1", /*turn letter*/"x")

a.visualize()
/*returns:
❌|ㅤ|ㅤ
ㅤ|ㅤ|ㅤ
ㅤ|ㅤ|

*/
```

## Git Repo
[tic-tac-nano-2](https://github.com/Bob09113/tic-tac-nano-2)

## Changelog
V1.0.0 - Initial Release<br />
V1.0.1 - Added the README.md file<br />
V1.0.2 - Added square lock to the turns<br />
V1.0.3 - Added a move log<br />
V1.0.4 - Added a draw condition
