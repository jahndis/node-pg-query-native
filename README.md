# pg-query-native

The real PostgreSQL parser for nodejs.

This is based on the output of [libpg_query](https://github.com/lfittl/libpg_query). This wraps the static library output and links it into a node module for use in js.

All credit for the hard problems goes to [Lukas Fittl](https://github.com/lfittl).

## Example

```js
var parse = require('pg-query').parse;

console.log(parse('select 1').query);
```

## Related

* [libpg_query](https://github.com/lfittl/libpg_query)
* [pg_query](https://github.com/lfittl/pg_query)
* [pg_query.go](https://github.com/lfittl/pg_query.go)