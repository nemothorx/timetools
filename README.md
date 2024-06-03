# Nemo's timetools

This is a collection of personal helper scripts for dealing with chronology
...For people who have moved past (the pretty neat idea of) digital watches 

* timescreen - big clock on your terminal - display the time in figlet fonts
* showtime - given a number of seconds, turns it into days/hours/etc
* worldtime - show the current time in multiple different timezones
* datediff - show time between two dates (uses showtime)


## timescreen

A nice full-screen clock

Originally designed to run in `screen` continuously, hence name

Time rendered big via figlet/toilet

### Example gif or it didn't example

![timescreen.gif](https://github.com/nemothorx/timetools/assets/455930/f9b28c02-d537-436f-9f05-97e504c18f63)


## Worldtime - show times around the world. 

Usage. 

`worldtime`

Advanced usage - show times of a different time. 

`worldtime <date(1) compatible date/time string>`
eg
`worldtime '19 may 2021 03:00'`

Super advanced usage - show times of a different time given in a different timezone

eg"
`worldtime '19 may 2021 18:00 BST'`
or
`TZ=Europe/London worldtime '19 may 2021 18:00'`

note. worldtime uses datediff


## datediff

Display the different between two date(1) compatible dates. 

eg: 
`datediff "01-Jan-1970" "@155555555"`

note: datediff uses showtime


## showtime

Show the time for a given number of seconds. 

eg: 
 `showtime 155555555`

----

## TODO: 

Improve usage details 

----

## History

These scripts were created and updated independently to each other over many
years, then assembled into this repo in 2024 from backups. Details of this
process can be found in the earliest commits. 

