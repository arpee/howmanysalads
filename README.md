# howmanysalads
Just how many salads do I owe Dave for.

##Usage:

* Add a salad
$ date >> salads

* calculate owings
(cat price; wc -l < salads) | paste -s -d\* | bc

* set price
echo <new price> > price
