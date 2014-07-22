## Idiomatic Method Naming to Language Convention

While we are going to [maintain standard method naming conventions](completed/METHOD_NAMING.md), we will provide convenience functions that make the library idiomatically correct in each language.

Readmes will contain examples for both the library _and_ language standard, as so:

```rb
# you can convert the string to json by using the standard
header.to_json
# or you can use the method common across the sendgrid libraries
header.json_string
```

All implementation of the methods will happen in the standard method, and thus the idiomatic standard needs only to act as an alias, however if the idiom would require additional code to function correctly, it may be implemented, and rely on the "SendGrid Standard" to manipulate the email object (e.g.)

