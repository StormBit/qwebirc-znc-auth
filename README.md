# qwebirc znc-auth fork
Fork of [qwebirc](<http://qwebirc.org>) used by [StormBNC](<https://stormbit.net/help/stormbnc>) to make a web-client for the [ZNC](<http://znc.in>) bouncer service.

## Requirements and Installation
See [http://qwebirc.org/installation](<http://qwebirc.org/installation>)

***tl;dr***
```
python python-twisted python-twisted-bin python-twisted-core python-twisted-runner python-twisted-names python-twisted-mail python-twisted-words python-twisted-web python-zope.interface python-openssl openjdk-6 mercurial
```

## Changes
Adds another box on the Connect pane, changes some underlying things in regards to the initial IRC connection code, and some minor UI details

## Issues
Report in the Issues section

## Original README contents
```
Installation instructions are on the website:
http://qwebirc.org/faq

If you'd like to make modifications you'd find it a LOT
easier if you symlink:

js -> static/js/debug
css -> static/css/debug

... then you can browse to http://instance/quidebug.html
and use your favourite javascript debugger, as well as
not having to compile each time you make a change!
```
