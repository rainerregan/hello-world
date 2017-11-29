Hello World
=========
A small library that write hello world to you

# Test out my module
Create a folder and `package.json` file.
`````
{
  "dependencies": {
    "helloworld-rainer": "*"
  }
}
`````

then write in command line
`npm i`

Now create an index.js with content below

````
var helloIdx = require('helloworld-rainer');
var helloText = helloIdx('##YOURNAMEHERE');

console.log(helloText);
````
*change ## YOURNAMEHERE with your name

and run the code with `node index`

you will see the output with your name... :D

# Build

[![Build Status](https://travis-ci.org/rainerregan/hello-world.svg?branch=master)](https://travis-ci.org/rainerregan/hello-world)
[![Coverage Status](https://coveralls.io/repos/github/rainerregan/hello-world/badge.svg?branch=master)](https://coveralls.io/github/rainerregan/hello-world?branch=master)

## Installation

  `npm install helloworld-rainer`

## Usage

    var helloInx = require('../index');
    
    var hello = helloInx("#WRITE YOUR NAME HERE");
  
  
  Output should be `Hello world, Nice to meet you #YOUR NAME :D`


## Tests

  `npm test`

## Contributing

In lieu of a formal style guide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code.
