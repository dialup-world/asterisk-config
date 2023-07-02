# asterisk-config
Asterisk configuration

Included are selected bits of `asterisk` config to get the ATAs registered to the server, and to get incoming calls from voip.ms and the WEBTV toll-free number by registering to their respecitive servers as defined in `sip.conf`. 

Incoming calls from these sources and generic WebTV credentials go to a context block in `extensions.conf` that will route the call to the modem bank. All of this could be done with one context, but three separate ones are used if something specific needs to be changed at a later date.
