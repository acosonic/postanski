# postanski
This module returns postal numbers of cities in Serbia

Nodejs Poštanski brojevi modul
# Installation

`npm i postanski`


# Usage:


`const postbr = require('postanski');

postbr.postanski('naziv mesta');`

It uses similarity alogrithms to find matching city.

For example:

Beograd Savski ven (it will return post number of Beograd Savski Venac)