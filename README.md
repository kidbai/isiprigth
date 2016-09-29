check ip is right.

## Usage
    npm install isipright
    var isipright = require('isipright')

    isipright.check('127.0.0.1')  // return ture
    isipright.check(['127.0.0.1', '11.11.11.11'])   // return false
    isipright.check(['127.0.0.1', '11.11.a1.11'])
    isipright.check(['127.0.1', '11.11.11.11'])

## LICENSE

MIT
