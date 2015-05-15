# mixtag
Ecosystem for generating transitional mixes based on advanced audio metadata. This project can be split into these aspects:

## the mixtag filetype
In a nutsheell: audio fingerprint + MIDI synced to fingerprint + extra metadata, e.g. which sections are choruses, verses, instrumental breaks, etc. It will probably be based on Echoprint or some other open source audio fingerprint system.

## the mixtag file creator
We will target multiple platforms, including the web. 

## the mixtag database and API
All apps, and of course, the website, should allow easy upload to a database or databases of these mixtag files. These should be easily navigable, queryable, rateable, sharable, all that jazz.

## the mixtag analyzer and mix maker, and mixmash filetype
Such a program can import mixtag files and analyze them, along with the associated songs in the user's library. Various parameters and levels of control can be set. Multiple programs can be made to cater for casual consumers who just want to "fire-and-forget" a mix, to live-performing professional DJs. These mixes can be saved and shared as their own type of file, tentatively dubbed a mixmash.