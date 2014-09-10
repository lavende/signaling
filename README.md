# signaling server [ecclesia]


### orginal content

A simple signaling server for clients to connect and do signaling for WebRTC.

Specifically created as a default connection point for [SimpleWebRTC.js](https://github.com/HenrikJoreteg/SimpleWebRTC)

It also supports vending STUN/TURN servers with the shared secret mechanism as described in [this draft](http://tools.ietf.org/html/draft-uberti-behave-turn-rest-00).  This mechanism is implemented e.g. by [rfc-5766-turn-server](https://code.google.com/p/rfc5766-turn-server/) or by a [patched version](https://github.com/andyet/otalk-server/tree/master/restund) of [restund](http://creytiv.com/restund.html).

### mexan comment

This is a fixed version of signaling server creaeted specially for ecclesia.
