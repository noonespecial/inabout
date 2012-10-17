inabout
=======

Shell script to drop into the background and execute a command "inabout" some length of time.

This small .sh script was the smallest, simplest possible thing I could come up with that
would sleep a given amout of time detatched and in the background and then execute a command.

I created it for use with OpenWRT boxes that had no cron utilities.

Perfect for setting if to reboot an hour from now even if you lose your connection. 

Put it somewhere in your path. Use like so:
$# inabout 30 minutes "reboot"