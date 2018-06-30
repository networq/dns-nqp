networq:dns
====

This is the "networq:dns" package for [NetworQ](https://github.com/networq).

## Types

This package defines the following types that you can use in your own Networq:

### networq:dns:record type

Fields:

  * `domain`: *networq:dns:domain*
  * `name`: *string*
  * `type`: *string*
  * `ttl`: *string*
  * `value`: *string*

### networq:dns:domain type

Fields:

  * `name`: *string*
  * `records`: *networq:dns:record[]*
  * `primary-nameserver`: *string*
  * `secondary-nameserver`: *string*


