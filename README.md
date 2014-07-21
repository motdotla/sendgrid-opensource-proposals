# Proposals for SendGrid open source

This document is a moving target and likely temporary. It's a tool to workout brining our open source libraries closer inline together.

## Proposals

* <del>[Drop SMTP support from libraries](http://github.com/scottmotte/sendgrid-opensource-proposals/blob/master/proposals/completed/DROP_SMTP.md)</del>
* <del>[Unify naming for SMTPAPI libraries](http://github.com/scottmotte/sendgrid-opensource-proposals/blob/master/proposals/completed/METHOD_NAMING.md)</del>
* [Port](https://github.com/scottmotte/sendgrid-opensource-proposals/blob/master/proposals/PORT.md)

## Summit

### Past few months

* Goal: Stable libs. It's an ongoing battle, but we did it. I'd consider our libs stable.
* New: sendgrid-ruby
* New: [nodemailer-sendgrid-transport](https://github.com/sendgrid/nodemailer-sendgrid-transport)
* New: sendgrid-apex (salesforce)
* New: smtpapi-objc

### Low Hanging Fruit

* Objective C library to be transfered under SendGrid GitHub. Currently a fork.

### Discuss and Decide

* Discuss and Decide: Python and Go libs ready for 1.0?
* Discuss and Decide: To be idiomatic or not to be idiomatic. [1](https://github.com/scottmotte/sendgrid-opensource-proposals/commit/5b2d1745044c08b5a01d9f113583a906bf2760d4#commitcomment-6921910)
* DONE (Eddie making it happen): Discuss and Decide: User agent to libs.
* Discuss and Decide: Awwa more involved. Begin by pulling in Awwa's smtpapi lib. Before or after my vacay.
* Discuss and Decide: Yamil's pythong library BCC approach. Multiple emails in the to field vs not multiple in to. Historic approach vs future approach. 

## Status - 32

### SMTPAPI Libs - 3

* <https://github.com/sendgrid/smtpapi-csharp> 1
* <https://github.com/sendgrid/smtpapi-go> 0
* <https://github.com/sendgrid/smtpapi-java> 1
* <https://github.com/sendgrid/smtpapi-nodejs> 0
* <https://github.com/sendgrid/smtpapi-php> 0
* <https://github.com/sendgrid/smtpapi-python> 1
* <https://github.com/sendgridjp/smtpapi-ruby> 0

### Libs - 19

* <https://github.com/sendgrid/sendgrid-csharp> 5
* <https://github.com/sendgrid/sendgrid-go> 0
* <https://github.com/sendgrid/sendgrid-java> 9
* <https://github.com/sendgrid/sendgrid-nodejs> 0
* <https://github.com/sendgrid/sendgrid-php> 4
* <https://github.com/sendgrid/sendgrid-python> 1
* <https://github.com/eddiezane/sendgrid-ruby> 0

#### Libs without SMTPAPI sub-libs - 10

* <https://github.com/sendgrid/sendgrid-apex> 0
* <https://github.com/sendgrid/sendgrid-objc> 3
* <https://github.com/sendgrid/sendgrid-perl> 7
