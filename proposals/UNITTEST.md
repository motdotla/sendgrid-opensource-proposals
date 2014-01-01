# Std Unittest for all libraries

Currently we do testing in different ways. I want to make a simple standard that should work accross all languages. Basically, build a string that contains everything for a request that contains a file, headers etc.

## Example

```
assert("{"to":"scott@sendgrid.com", "file[pic.jpg]": "somebinaryrepresentationofthis", "x-smtpapi": "themjson"}", "{"to":"yamil@sendgrid.com"}") => false
```

Simple as that. It will test literally everything. And can be used in travis too

## Proposed file:

<https://github.com/sendgrid/smtpapi-nodejs/blob/master/test/smtpapi_test_strings.json>
