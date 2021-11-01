# vinyl-ripper-helper

This is a branch of Scott C.'s excellent vinyl ripper utility.  It did about 99% of what I wanted in a helper app, and works great for several others.  However, for my own wants and needs, I wanted to change the way the script wrote tags, and used PyDub to add silence detection to the script.

I'm also removing the PDF from this fork; while it's an excellend and thorough manual, because I'm changing the functionality enought that it warranted a rewrite; rather than get Scott C.'s permission to edit his original document, I'm going to attempt to write some abridged instructions in a Free format like Markdown.

This fork is a work in progress; feel free to consult ScottC's repo for the original stable script.

*original text follows*

VinylRipperHelper, or VRH is a Python utility for people who use the free software Audacity application to “rip” vinyl LP records and tapes to digital format.  To use VRH in its initial version, one first needs to make a recording of an album that he/she would like to rip.  Then one needs to download the tracklist page for the album being ripped from the Discogs.com website.  

Then run VRH, and it will 1) extract the track list and times, and use them to create the labels that are needed to identify all of the songs on the recording.  VRH will also 2) Create a “tags” template file to use with the Audacity metadata editor. This file provides all of the XML tags for the album including the title, artist, genre, year, plus any other tags that were listed for the album in the discogs.com tracklist page.

Combined together, these two files substantially reduce the amount of time-consuming data entry required to perform the process for exporting multiple tracks to individual song files with Audacity.

There's a detailed PDF manual for using VRH in this repository, with some help for those new to using Audacity to rip vinyl and tape.

VinylRipperHelper is GNU Public License v3 (GPLv3) licensed software, please contribute if you have ideas for bug fixes or improvements.
VRH is developed and maintained by Scott Chilcote, scottch1 @ github.com
