postgresql_auto_backup_s3
=========================

Configurable backup scripts to automate postgresql backups and push to s3 via stdin, plus rotation logic

Original code from https://wiki.postgresql.org/wiki/Automated_Backup_on_Linux.

Will be adapted to work with s3cmd stdin pushing, there fore needs s3cmd >= s3cmd 1.5.0-alpha1 , also see http://s3tools.org/news
