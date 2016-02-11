Better GUID
===========

A Node.js packaged implementation of the Firebase Push Ids as detailed here: [https://www.firebase.com/blog/2015-02-11-firebase-unique-identifiers.html](https://www.firebase.com/blog/2015-02-11-firebase-unique-identifiers.html).

Generates unique identifiers that are sequentially sorted according to time.

Usage
-----

```
const guid = require('betterguid')()

var id = guid()
```

Examples:

```
var guid = require('betterguid')()
> guid()
'-KAH__m6RdwSQLqwTQ73'
> guid()
'-KAH__waK0ArlUVpp_0C'
> guid()
'-KAH_a1DQiDIe-2JP8YX'
> guid()
'-KAH_a65JuorbJUB8dUV'
> guid()
'-KAH_aAqImxK0dQ2Iv3g'
> guid()
'-KAH_aFUVo59MG4pqgnu'
> guid()
'-KAH_aK5B2ts3PgcmmD_'
> guid()
'-KAH_aOkO1QnTi5nFYeO'
> guid()
'-KAH_aTiKFZl1WVOh7jX'
> guid()
'-KAH_aYrUpn0Lx5_oaaA'
> guid()
'-KAH_acrVTYYIcEQRj92'
> guid()
'-KAH_ahrVn5qx6TKeERB'
```
