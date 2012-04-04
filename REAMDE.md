# Mozillians Mysql Anonymous #

Based on @davedash's
[Mysql Anonymous](https://github.com/davedash/mysql-anonymous), this script
simply filters out sensitive data from a Mozillians MySQL dump so developers
can have production-like data without sensitive user data.

## Usage ##

    python anonymize.py > anon.sql
    cat anon.sql | mysql
