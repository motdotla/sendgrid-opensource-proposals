# Ability to change host/port on libraries

Proposed: Each of our libraries should offer the ability to change the host/port.

Newly Proposed: 

* setUrl - default to: https://api.sendgrid.com
* setEndpoint - default to: /api/mail.send.json

## Complete (sort of. non-standardized)

Some are host, port, endpoint. Some are just endpoint. Some are just url. Some have methods like setUrl, setEndpoint.

* java - <https://github.com/sendgrid/sendgrid-java/blob/master/src/main/java/com/sendgrid/SendGrid.java#L34>
* nodejs (sort of) - <https://github.com/sendgrid/sendgrid-nodejs/blob/master/lib/sendgrid.js>
* go (sort of) - <https://github.com/sendgrid/sendgrid-go/blob/master/sendgrid.go#L21>
* python (sort of) - <https://github.com/sendgrid/sendgrid-python/blob/master/sendgrid/sendgrid.py> 
* php (sort of) - <https://github.com/sendgrid/sendgrid-php/blob/master/lib/SendGrid.php#L20>

@elbou8 you've added most of these. What do you think the standard should be? 
