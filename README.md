# Pluralize-fr

> Finds the plural form of most french words.  Many exceptions are covered.

## Installation
```
$ npm install --save pluralize-fr
```

## Usage

```js
var plural = require('pluralize-fr');

plural('jambe');
//=> 'jambes'

plural('oeil');
//=> 'yeux'
```

## API

### plural(str)

#### str

Type: `string`

The noun to make plural.
