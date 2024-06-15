### MySQL advanced

# author: Fatima zohra ezzaidani

# Concept:

- create tables with constraints
- optimize queries by adding indexes
- implement stored procedures and functions in MySQL
- implement views in MySQL
- implement triggers in MySQL

# Requirements:

- Ubuntu 18.04 LTS using MySQL 5.7 (version 5.7.30)
- Ask for container Ubuntu 18.04 - Python 3.7
- Connect via SSH or via the WebTerminal
- In the container, you should start MySQL before playing with it: ```$ service mysql start

* MySQL Community Server 5.7.30 is started
  $
$ cat 0-list_databases.sql | mysql -uroot -p my_database
  Enter password:
  Database
  information_schema
  mysql
  performance_schema
  sys
  $ ```

- In the container, credentials are root/root
