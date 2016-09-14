# crontab
OVERVIEW
The crontab command can easily overwrite your crontab file, erasing it permanently. This can happen when one either purposefully
or accidentally invodes crontab with the -r switch. It can also happen if one enters the crontab command without any parameters (
which enters a mode that allows for you to enter commands via standard input) and try to get out of it by typing command-d instead
of control-c. As a result, your crontab isn't secure unless it is backed up in version control.

INSTRUCTIONS
Add your own crontabs here. Each user can have multiple crontab files since there is a crontab per host machine they work with. For each of your crontab files in this repository, name it beginning with your SUNet ID, followed by an underscore, followed by the host name, i.e. nathankw_dirk-new.

You can load your crontab into memory by issuing the command

  crontab $INFILE
  
where $INFILE is the system path to your crontab.

Don't use "crontab -e" to edit your crontab anymore, because this won't change your versioned file. Instead, directly edit the file you have in this repos, then reload it into memory with "crontab $INFILE".

