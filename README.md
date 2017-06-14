# auto-xtrbackup
this shell helped you automatic backup mysql database by xtrbackup.

make sure u already install Percona XtraBackup, then you can just put into below folder and grant executble permission(chmod):
```sh
/usr/local/bin/
```
and you can full backup by this command 
```sh
umbackup -b full
```
and incermental backup
```sh
umbackup -b inc
```
those backup file will create at 
```sh
/data/backups/
```

and you can execute frequency by add to crontab.
more crontab detail see:
https://www.computerhope.com/unix/ucrontab.htm
