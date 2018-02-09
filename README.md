# SQL92-keywords

> is the list of reserved words in SQL92 specification

[Installation](#installation) |
[Usage](#usage) |
[License](#license)

## Installation

With [npm](https://npmjs.org/) do

```bash
npm install sql92-keywords
```

## Usage

Get keywords list.

```javascript
const keywords = require('sql92-keywords')
```

Note that all keywords are in upper case.

```javascript
keywords.indexOf('SELECT') > -1 // true
keywords.indexOf('Select') > -1 // false
```

## License

[MIT](http://g14n.info/mit-license/)
