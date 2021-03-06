# Release notes

## 1.8.0
Sep 2, 2019
* Add --start-from to backup action
* Add --detail to list action
* Add --all param to export
* Fix restore for windows enviroment

## 1.7.0
Jul 25, 2019
* Add --delete-host/-D parameter to config
* Add --clean/-c parameter to config
* Add --exclude/-E to backup and restore

## 1.6.0
Jun 20, 2019
* Add second argument of --retention param
* Add param --bwlimit, than specify bandwidth limit
* Add docstring in script
* Add --ssh-port parameter

## 1.5.0
May 17, 2019
* Add --rsync custom path option
* Add config function --init; reset catalog backup file

## 1.4.0
Jan 8, 2019
* Add one-line option in list function
* Add Differential backup mode
* Add Code Of Conduct
* Add man page into command line

## 1.3.0
Oct 23, 2018
* Add list archived backups only
* Add list cleaned backups only
* Add dry-run mode
* Fix documentation and change theme

## 1.2.0
Oct 5, 2018
* Add last option for restore mode
* Add mirror option for restore mode

## 1.1.0
Aug 31, 2018
* Add timeout option
* Fix documentation #1 .Thanks Jack

## 1.0.0
Aug 9, 2018
### A butterfly is born from the chrysalis...welcome Butterfly Backup

* Configuration for silently backup
* All backup are organized into a catalog
* List single or all backup by the catalog
* Backup single PC, with Full,Incremental and Mirror mode;
* Backup more PCs, with Full,Incremental and Mirror mode (with parallelism algorithm);
* Backup custom folder or predefined data (User,Config,Application,System,Log)
* Restore backup on the same PC
* Restore backup in other PC
* Restore backup in other operating system
* Apply retention policy to delete old backup
* Archive old backup in other file system or same (zip backup folder)