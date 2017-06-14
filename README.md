# auto-xtrbackup
automatic backup mysql database by xtrbackup

make sure u already install Percona XtraBackup, then you can just put into below folder and grant executble permission(chmod):
/usr/local/bin/
and you can full backup by type command by console
umbackup -b full
and incermental backup
umbackup -b inc

and you can execute frequency by add to crontab.
more crontab detail see:
https://www.computerhope.com/unix/ucrontab.htm
