# crontab
OVERVIEW
The crontab command can easily overwrite your crontab file, erasing it permanently. This can happen when one either purposefully
or accidentally invodes crontab with the -r switch. It can also happen if one enters the crontab command without any parameters (
which enters a mode that allows for you to enter commands via standard input) and try to get out of it by typing command-d instead
of control-c. As a result, your crontab isn't secure unless it is backed up in version control.

INSTRUCTIONS
Add your own crontabs here. Each user has one crontab and the file is named after their SUNetID.

You can load your crontab into memory by issuing the command

  crontab $INFILE
  
where $INFILE is the system path to your crontab.

