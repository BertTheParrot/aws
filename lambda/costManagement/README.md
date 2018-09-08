# Stop/Start scripts

For the start up and shut down scripts, tag instances with following tags

AutoOn : True
AutoOff: True

Add CloudWatch events, all in GMT.
ex
cron(0 01 ? * MON-FRI)
