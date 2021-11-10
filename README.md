# Nemo's Timetools

This is a collection of personal helper scripts for dealing with chronology
...For people who have moved past (the pretty neat idea of) digital watches 


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

