Broadcast
=======

_Difficulty_: __Intermediate__

A web-app that allows creating a message channel service. A registered user can create her channel. A channel can be joined by subscribers using SMS. The channel admin can then send SMS broadcasts to the sunscribers.

## Specifications ##

The web-app uses [Plivo](http://plivo.com) / [Twilio](http://twilio.com) APIs for the SMS gateway. The app should dynamically create channels on these APIs and dynamically add subscribers. Subscribers can be added manually through the web interface as well as using the SMS service (whiich could be pricey, though). Both these services provide a Python API, so the server-code could use that, or (preferably) use the RESTful APIs.

### Implementation ###

* Language: [Python](http://python.org)
* Web Framework: [Flask](http://flask.pocoo.org)
* APIs: [Plivo](http://plivo.com) / [Twilio](http://twilio.com)
