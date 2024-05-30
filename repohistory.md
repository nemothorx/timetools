# Nemo's timetools

This is a collection of personal helper scripts for dealing with chronology
...For people who have moved past (the pretty neat idea of) digital watches 

* timescreen - big clock on your terminal - display the time in figlet fonts
* showtime - given a number of seconds, turns it into days/hours/etc
* worldtime - show the current time in multiple different timezones
* datediff - show time between two dates (uses showtime)

These scripts were created independently to each other over several years with
no thought of them being part of a collection, despite datediff having a
dependency on showtime from it's start. Otoh worldtime, despite dating back to
2005, didn't gain its dependency on datediff till 2021. In this repo they're
formally declaring themselves not just dependent, but related. 

timescreen was originally compiled into a `timescreen` repo in 2023, with
`showtime`, `worldtime` and `datediff` intending to be their own repo with the
idea that it would have three branches to indicate the three original scripts,
and reconstruct a logical history of them as best as possible. However this was
never done, and in 2024 saner heads prevailed and thus created here as just
a linear progression of them without complex branching. ie, just as could have
been found in my ~/bin at the time. Plus I extracted the timescreen repo and
added its history in here too.

Thus this repo was (finally!) constructed in 2024, using chronocsv2git.sh (from
my neon-git repo) helper tool to import the trawled-from-backups versions of
the scripts. git-timemachine (also from neon-git) ensured all commit times
match the original mtime of the scripts themselves. The script was controlled
by cronogit.csv and it along with an automatically created chronogit.md are
commited to the repo as part of the process of documenting the construction of
this after-the-fact git history. 

Note that despite the name, git-timemachine is part of my neon-git tools, not
this timetools collection.

https://github.com/nemothorx/neon-git

Note also: the files being added were found by trawling old backups, and
renamed to organise them for processing. There are some signifant gaps in
version histories. Despite this, some minor revision have not been included
for the sake of a cleaner repo.
