# Ability to change host/port on libraries

Proposed: Each of our libraries should offer the ability to change the host/port.

Newly Proposed & Accepted: 

* Protocol (`https`, `http`) - Maybe your environment only allows for HTTP connections.
* Host (`api.sendgrid.com`, `secret-hostname.sendgrid.com`, `bucket.runscope.io`) - For things like Runscope or HV customers
* Port (`80`, `443`) - Maybe you're an engineer testing our mail pipeline and you have it running on a weird port
* Endpoint (`/api/mail.send.json`) - _I dunno what else you'd do, but maybe in the future this is useful_
* URL as a whole (`https://api.sendgrid.com/api/mail.send.json`) - for simplicity's sake

## Complete (sort of. non-standardized)

Some are host, port, endpoint. Some are just endpoint. Some are just url. Some have methods like setUrl, setEndpoint.

* java - <https://github.com/sendgrid/sendgrid-java/blob/master/src/main/java/com/sendgrid/SendGrid.java#L34>
* nodejs (sort of) - <https://github.com/sendgrid/sendgrid-nodejs/blob/master/lib/sendgrid.js>
* go (sort of) - <https://github.com/sendgrid/sendgrid-go/blob/master/sendgrid.go#L21>
* python (sort of) - <https://github.com/sendgrid/sendgrid-python/blob/master/sendgrid/sendgrid.py> 
* php (sort of) - <https://github.com/sendgrid/sendgrid-php/blob/master/lib/SendGrid.php#L20>

@elbou8 you've added most of these. What do you think the standard should be? 
