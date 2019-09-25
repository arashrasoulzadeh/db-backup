# GoBackup :floppy_disk:

GoBackup is a `mysqldumper` wrapper to full/partial backup and/or compress mysql databases. 

## Download
You can download the release file from [releases](https://github.com/YasnaTeam/db-backup/releases) page.

## Usage
You can see usage with --help flag

| Flag        | Usage           | Default  |
| ------------- |:-------------:| -----:|
| t     | name of table(s) you want to dump comma separated. | * |
| n      | output file name      |   dump |
| p | output file path      |     |
| f     | output file type (sql,zip,gz) | sql |
| d     | add date to output file | false |
| db_user      | database user name      |    |
| db_pass | database user password      |     |
| db_host     | database host |  |
| db_name      | database name      |    |
| db_port | database port number      |    3306 |
| config | database config file      |     |


## Contribution :love_letter:

Fork project and send PR to me :heart: