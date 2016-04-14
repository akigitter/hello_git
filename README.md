# hello_git
# simple
// hello.js
console.log("Hello World")
# using chalk
// hellochalk.js
// play around with node.js and chalk
const chalk = require('chalk');

console.log(chalk.yellow("Hello JavaScript chalk"));
// nest styles of the same type even (color, underline, background)
// hellochalk.js
// play around with node.js and chalk
const chalk = require('chalk');

console.log(chalk.yellow("Hello JavaScript chalk"));

// nest styles of the same type even (color, underline, background)
console.log(chalk.green(
     'I am a green line ' +
         chalk.blue.underline.bold('with a blue substring') +
             ' that becomes green again!'
             ));
