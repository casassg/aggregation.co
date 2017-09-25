aggregation.co
==============
This code implements an RSS aggregator website using PHP.  It requires the use of a database to hold information about RSS feeds.

The code uses SimplePie to collect RSS feeds that are then tucked into the
database.

This code is currently used by the site http://aggregation.co

## Install

```
mysql -u root < install.sql
mysql -u aggreagate -p < tables.sql
```

You will need to input a password for the 2nd command. This password is "hola". You can change the default password, user and database on the `install.sql` and `tables.sql`.


