
# console-log

A simple function that wraps `console.log` to log various types of inputs to the console. Use it to easily log different data types and values.

## Installation

Install the package via npm:

```bash
npm install console-log
```

## Usage

Simply require the `console-log` package and start logging:

```javascript
const consoleLog = require('console-log');

consoleLog("Testing");
consoleLog(3 + 4);
consoleLog(3 == 4);
consoleLog(1 + "0");
consoleLog(typeof true);
consoleLog(undefined);
consoleLog(null);
```

This will log the output of various expressions to the console.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
