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

*optional

| Nodejs              | PHP                 | Python             | Golang             | Proposed camel or snake |
| --------------------| ------------------- | ------------------ | ------------------ | ----------------------- |
| addTo               | addTo               |                    |                    | addTo                   |
|                     |                     |                    |                    | REMOVE                  |
| setTos              | setTos              |                    |                    | setTos                  |
|                     |                     |                    |                    | REMOVE                  |
| addSubstitution     | addSubstitution     | add_substitution   | AddSubstitution    | addSubstitution         |
| setSubstitutions    | setSubstitutions    | set_substitution   |                    | setSubstitutions        |
| addUniqueArg        | addUniqueArg        | add_unique_args    | AddUniqueArg       | addUniqueArg            |
| setUniqueArgs       | setUniqueArgs       | set_unique_args    |                    | setUniqueArgs           |
| addCategory         | addCategory         | add_category       | AddCategory        | addCategory             |
|                     |                     | set_category       |                    | REMOVE                  |
| setCategories       | setCategories       |                    |                    | setCategories           |
|                     |                     |                    |                    | REMOVE                  |
| addSection          | addSection          | add_section        | AddSection         | addSection              |
| setSections         | setSections         | set_section        |                    | setSections             |
| addFilter           | addFilter           | add_filter         | AddFilter          | addFilter               |
| setFilters          | setFilters          |                    |                    | setFilters*             |
|                     |                     |                    |                    | REMOVE                  |
|                     |                     |                    |                    | REMOVE                  |
|                     |                     |                    |                    | REMOVE                  |
| jsonString          | jsonString          | api_header_as_json | GetHeaders         | jsonString              |




