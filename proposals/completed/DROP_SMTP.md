# Drop SMTP support

Drop SMTP support from our open source libraries. The Web API is 2-3 times faster. Additionally, this will save us lots of coding time. It's been expensive maintaining SMTP support simluatneously in the libraries.

Along with this proposal, we need to pull out the X-SMTPAPI header generation code into their own libraries. That way developers can still choose to use SMTP with the popular SMTP client of their choice in the language of their choice. They can use our X-STMPAPI header generation library to make it easy to still use with SendGrid.

A complete SMTP example should be included in each language using these SMTPAPI header generation libraries.

This proposal is already underway and moving quickly.
