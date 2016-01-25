# Installation notes

# Requirements #

Well ... netdisco to start with, a web serve is also usefull (Apache2)


# Details #

  * Fetch the latest source package from https://code.google.com/p/netdisco-visual .
  * Unpack
  * Create a location for the netdisco-visual web page (for example /srv/www/IN) and make sure your web server can serve it
  * Copy netdisco-visual-0.1/htdocs/IN content to a the previously created directory
  * Patch your netdisco core and configuration files with the the diffs available in netdisco-visual-0.1/netdisco
  * Change in netdisco.conf the entry for graph\_json according to your install (for example /srv/www/INdata/netmap.json)

Browse to the location you have just created.