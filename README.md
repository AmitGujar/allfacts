# allfacts

A NPM Package for quotes. The database currently includes more than 15000 facts.

freefactsdk library is just wrapper around https://github.com/AmitGujar/freeFacts

## Install

```
npm install allfacts --save
```

## Usage

Get random fact

```javascript
const { getRandomFacts } = require("allfacts");

getRandomFacts()
  .then((fact) => {
    console.log(fact);
  })
  .catch((err) => {
    console.log(err);
  });
```

## Contributing

All feedback and contributions are welcome!
