# shorty
_shorty_ is a simplistic Short-URL generator

Short URLs are nice for many reasons, but using 3rd party services to create and
store them can lead to trouble: tracking and other privacy invading behaviour,
possibly hiding drive-by malware and of course the risk that the 3rd party might
shutdown and links are lost.

_shorty_ is just a simple shell-script with dependencies on gawk, wget and
mktemp, thus it should be easy to run on pretty much any unixy system.

*WARNING*, currently the default is to redirect after 3 seconds which you might
want to change.

To actually use the generated URLs, just (r)sync the files/folders to your
server by any means you like.