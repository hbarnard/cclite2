Cclite2 February 2021

This the second version of Cclite, based on Mojolicious, Postgresql and a native RESTful interface. 
It's designed as an engine rather than a web application, but an html interface is still provided.

Currently testing on Linux Mint, therefore Debian and Ubuntu *should* be OK. It will *not work* as a Windows native now
as Cclite used to (no apologies), it'll *probably* work with `cygwin`, WSL etc. 

The deb package install is or whatever the current deb version is:
`sudo apt install ./cclite2_0.1-3.deb`

If you want to experiment with intertrading you will need rabbitmq: `https://www.rabbitmq.com/install-debian.html#apt`
We've chosen this, because it's stable and supports many of the pub/sub protocols. `SOAP` and cclite's registry <-> is gone 
as being clumsy, hard to debug and P2P only.  

The web templates are only in English, French and Spanish(machine translation, so imperfect) until spring 2021, they use Mojolicious EPL 
but there's much better separation of template and core, this time.

That's it, for the moment. Watch this space.

