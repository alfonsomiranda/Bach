#Bach 
###(I got the idea while someone plays Bach on the Subway)

A little script/test/application to download torrent (of series) from one or various sites, and automatize with my new raspberry pi

The script read an url and send the magnets to a transmission-daemon, before checking that we have not downloaded.

##use

**This project is an experiment**

Put the urls in the series.json file:

```
{
   '<site_name>', //only supported eztv yet
   [ '<urls' ]
 }
 ```

Exists an example in the file series.json_dist

The transmission-daemon config is in the file settings.py_dist you must rename to settings.py

run: `python bach.py`


##Improvements in progress:

Use inheritance properly in spiders.

Create more spiders
