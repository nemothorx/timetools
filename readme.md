# Nemo's Timetools 

This is a collection of personal helper scripts for dealing with chronology

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


## datediff - show the time difference between two dates

Any date(1) compatible date should work. Defaults to "now" if no second date given. 

eg: 
`datediff "01-Jan-1970" "@155555555"`

note: datediff uses showtime

## showtime - show the time for a given number of seconds

eg: 
`showtime 155555555`



## TODO: 
* Improve help/usage within scripts
