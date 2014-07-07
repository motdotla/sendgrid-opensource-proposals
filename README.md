# Proposals for SendGrid open source

This document is a moving target and likely temporary. It's a tool to workout brining our open source libraries closer inline together.

## Proposals

* <del>[Drop SMTP support from libraries](http://github.com/scottmotte/sendgrid-opensource-proposals/blob/master/proposals/completed/DROP_SMTP.md)</del>
* <del>[Unify naming for SMTPAPI libraries](http://github.com/scottmotte/sendgrid-opensource-proposals/blob/master/proposals/completed/METHOD_NAMING.md)</del>
* [Port](https://github.com/scottmotte/sendgrid-opensource-proposals/blob/master/proposals/PORT.md)

## TODOS

* add user_agent to the libs.
* Start the process of bringing in some of [Awwa](https://github.com/awwa)'s stuff to the main SendGrid GitHub.
* Obj C library should be transfered directly under SendGrid account <https://github.com/sendgrid/sendgrid-objc>. Currently a fork.
* Eddie's already getting the tracker agent to track versions of libraries being used. Working with Suchit on that.
* Go through the smtpapi libraries and try to standardize the unittests - using the given json file.
* smtpapi-java lib needs to be built for 1.6. Ask a Java person how to do this.

## Status

### SMTPAPI Libs

* <https://github.com/sendgrid/smtpapi-csharp> 1
* <https://github.com/sendgrid/smtpapi-go> 0
* <https://github.com/sendgrid/smtpapi-java> 1
* <https://github.com/sendgrid/smtpapi-nodejs> 0
* <https://github.com/sendgrid/smtpapi-php> 0
* <https://github.com/sendgrid/smtpapi-python> 1
* <https://github.com/sendgridjp/smtpapi-ruby> 0

### Libs

* <https://github.com/sendgrid/sendgrid-csharp> 5
* <https://github.com/sendgrid/sendgrid-go> 0
* <https://github.com/sendgrid/sendgrid-java> 4
* <https://github.com/sendgrid/sendgrid-nodejs> 0
* <https://github.com/sendgrid/sendgrid-php> 5
* <https://github.com/sendgrid/sendgrid-python> 0
* <https://github.com/eddiezane/sendgrid-ruby> 0

#### Libs without SMTPAPI sub-libs

* <https://github.com/sendgrid/sendgrid-apex> 0
* <https://github.com/sendgrid/sendgrid-objc> 2
* <https://github.com/sendgrid/sendgrid-perl> 6
