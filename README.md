# simple syncing -- backups, cloning, etc

backups are local and create dated directories..
push just sends a path to a remote system
pull just grabs a path from a remote system and copies local

script name determines the operation: backup.sync, push.sync, pull.sync

Just symlink syncer to the appropriate name.


## Configuration

syncer.config has the top level directory for backups as well as the normal rsync options.

see examples/ directory for config and exclude files

Add DELETE=yes to have --delete and --delete-excluded added
