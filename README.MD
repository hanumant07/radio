Radio
=====

A small library for controlling a pianobar installation using strings

## Installation

  npm install radio --save

## Usage

  var pianobar = require('radio');
  
  var entry = pianobar.cmd_supported("play music");
  
  pianobar.exe_cmd(entry);

## Tests

  npm test

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code.

## Release History

* 1.0.0 Initial release
