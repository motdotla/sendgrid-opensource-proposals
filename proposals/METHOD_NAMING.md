# Bring the SMTPAPI libraries method naming closely inline with each other across languages

The new smtpapi libraries should have method naming closely inline with each other.

The naming should follow that languages' approach to naming - camelcase or snackcase, etc where necessary.

Each language should strive to have the same methods working in the same manner.

Below is a table striving to be a complete list for each language.

Keep in mind that the x-smtpapi json methods are named and constructed like the following. I feel like we should strive towards matching that even if some are poorly named.

```javascript
to           = [];
sub          = {};
unique_args  = {}; 
category     = [];
section      = {};
filters      = {};
```

| Nodejs                  | PHP                     | Proposed              |
| ----------------------- | ----------------------- |-----------------------|
| addTo                   | addTo                   | addTo                 |
|                         | setTo                   | setTo                 |
|                         | setTos                  | REMOVE                |
|                         | removeTo                | REMOVE                |
|                         | setSubstitutions        | setSub                |
| addSubVal               | addSubstitution         | addSub                |
| setUniqueArgs           | setUniqueArgs           | setUniqueArgs         |
| addUniqueArgs           | AddUniqueArgs           | setUniqueArgs         |
| addCategory             | addCategory             | addCategory           |
| setCategory             | setCategory             | setCategory           |
|                         | setCategories           | REMOVE                |
|                         | removeCategory          | REMOVE                |
| setSection              | setSections             | setSection            |
| addSection              | addSection              | addSection            |
| setFilterSetting        | setFilterSetting        | setFilters            |
| addFilterSetting        | addFilterSetting        | addFilters            |
|                         | setHeaders              | REMOVE                |
|                         | addHeader               | REMOVE                |
|                         | removeHeader            | REMOVE                |
| toJsonString            | toJsonString            | toJsonString          |




