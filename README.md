Description
===========

A collection of codes that I made, which I also consider are worth making public.

Javascript
==========
Glitch script
-------------
Based on [Simon Hewitt's](http://sjhewitt.co.uk/2012/07/javascript-glitch-effect-glitch-js/ "Simon Hewitt's") glitch script, I've created an effect that simulates transmission glitch.
Demos:
* At [CTF 365](http://ctf365.com/ "CTF365")
* At [this page](http://93.114.42.133/~sandu/glitch_test/ "Glitch test page")

Python
==========
Geonames.org dump parser
------------------------
A tool to parse the dumped text files from [geonames.org](http://download.geonames.org/export/dump/ "geonames.org") and insert it into a SQLite3 database file.

To run it you can run it with: **python create_locations_db.py** and it will run with defaults.
Two parameters are given :
* **--out** or **-o** - the output file name for the SQLite3 DB; default is locations.sqlite3
* **--tmp-dir** or **-t** - the temp dir where to work; default is '.' (current directory)


