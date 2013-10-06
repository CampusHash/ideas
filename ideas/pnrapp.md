PNRApp
======

_Difficulty_: __Easy__

A simple python script which will check the status of your railway ticket PNR at regular intervals and notify you about it.

## Specifications ##

A command-line tool which will accept a valid PNR number, a deadline and a refresh rate. The script will run in the background and check the current status of the PNR at the provided refresh rate until the deadline. It will notify about the successive PNR status fetched, and write them to a log file.

## Implementation ##

* Language: [Python](http://python.org)