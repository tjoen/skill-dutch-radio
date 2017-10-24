# Dutch Radio skill

This skill streams radio from urls. It uses vlc so you have to install that with:
sudo apt-get install vlc

I changed mpg123 to vlc because it seems to hang less on raspberry pi.
Change the csv to add or change channels in to your own language.

It is based upon https://github.com/forslund/mycroft-media-skills/tree/master/swedishradio

## Current state

Working features:
 - turn on 3fm
 - turn on radio 1
 - turn on arrow classic rock

Known issues:
 - none, so far

TODO:
 - Add volume adjustment when using wakeword.
