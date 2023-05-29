# timescreen

A nice full-screen clock

Originally designed to run in `screen` continuously, hence name

Time rendered big via figlet/toilet

## Example gif or it didn't example

![timescreen.gif](https://github.com/nemothorx/timescreen/assets/455930/fa855a3e-5b53-4087-b712-14164829e51d)

## TODO's
 - some sanity checking on options - and existance of figlet and fonts...
 - controllable alarm clock
 - stopwatch/timer
 - able to run something external for chiming the hours (eg, `saytime` or `george`)
 - use tput rather than echo
 - set path to figlet as a variable

## BUGS
 - figfonts specified in rcfile may be overridden by the big fonts if the width is too wide...


## Version Log 

### 4.4 (2023 Apr 27)
 - removing "myinternet" info
 - replacing sleep with sleepenh for more accurate timekeeping
 - new LOLCAT ability (figlet output pipes into this processor)
 - fix tall+wide bug on groovybar
 - some cleanup of replacing explicit escape codes with tput

### 4.3 (2013 march 20)
 - removed chkmail option. I dont use that anymore. 
 - cleaned up the duobleheight groovybar (echo was adding unwanted newline)

### 4.2 (2012 feb 16)
 - using TOIlet instead of figlet. Still calls /usr/bin/figlet though,
      but -c (center) option is not available, so has been removed from
      script. Some leading spacing added in places to hackishly compensate. 

### 4.1 (late 2010ish)
 - barest minimum of changes from control codes to tput, so as to work in tmux
   ...not a full replacement. Just enough for my common use. 

### 4.x's (late 2000ish)
 - config file (-rc= )
 - figlet binary option (-figbin= )

### 3.x's (middle 2000ish)
 - double-width secondbar when width is wide enough
 - new commandline options for: (they should be obvious I hope)
      -w=xx	(set width) 
      -l	(turn on looping)
      -b	(turn on beeps)
      -f 	(turn on fortunes)
      -m	(turn on mail check)
      -s	(turn on secondbar)
      -fn1	(figlet font for date)
      -fn2	(figlet font for time)
      -d	(double-height secondbar)
 - screen not cleared on EVERY minute. Only when nescessary now.
 - improved sh compliancy (tested against ash mostly)
   and uses /usr/bin/zsh by default (5x better CPU performance
   compared to bash. marginally worse memory usage)
 - clock (not date tho) is in bold. easier to see :)

### 2.x's (early 2000)
 - function groovybar as a "second hand"
 - slightly better random fortune setup

### 1.x's (1999ish)
 - internal looping
 - argument for width
 - implemented random fortunes

### betas: (1998ish)
 - seperate scripts for different fonts. 
 - very basic execution of concept
 - no error checking, nothing fancy
 - no internal looping

