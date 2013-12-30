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

| Nodejs              | PHP                 | Python             | Golang             | Proposed camel or snake |
| --------------------| ------------------- | ------------------ | ------------------ | ----------------------- |
| addTo               | addTo               |                    |                    | addTo                   |
|                     | setTo               |                    |                    | REMOVE                  |
|                     | setTos              |                    |                    | setTos                  |
|                     | removeTo            |                    |                    | REMOVE                  |
|                     | setSubstitutions    | set_substitution   |                    | setSubstitutions        |
| addSubVal           | addSubstitution     | add_substitution   | AddSubstitution    | addSubstitution         |
| setUniqueArgs       | setUniqueArgs       | set_unique_args    |                    | setUniqueArgs           |
| addUniqueArgs       | addUniqueArgs       | add_unique_args    | AddUniqueArg       | addUniqueArg            |
| setCategory         | setCategory         | set_category       |                    | REMOVE                  |
| addCategory         | addCategory         | add_category       | AddCategory        | addCategory             |
|                     | setCategories       |                    |                    | setCategories           |
|                     | removeCategory      |                    |                    | REMOVE                  |
| setSection          | setSections         | set_section        |                    | setSections             |
| addSection          | addSection          | add_section        | AddSection         | addSection              |
| setFilterSetting    | setFilterSetting    |                    |                    | setFilters              |
| addFilterSetting    | addFilterSetting    | add_filter         | AddFilter          | addFilter               |
|                     | setHeaders          |                    |                    | REMOVE                  |
|                     | addHeader           |                    |                    | REMOVE                  |
|                     | removeHeader        |                    |                    | REMOVE                  |
| toJsonString        | toJsonString        | api_header_as_json | GetHeaders         | toJsonString            |




