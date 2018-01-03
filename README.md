# xmysqlimport

xmysqlimport is small shell script based utility to help you import large databases. This is simple setting of a few MYSQL/MARIADB variable set and execute import.
How to use
  - download this repo as zip and extract
  - copy xmysqlimport to /usr/local/bin to make it globally available
  - use :)

# Usage
xmysqldump -f filename.sql -d database_to_import_in -u mysql_user -p mysql_password -h mysqlhost
  - usually mysql host is localhost/127.0.0.1 if working on development environment
