pg_doctor
=========

Alpha status so far. It will eat your kittens. 

A script to check the "health" of your PostgreSQL server. What should be checked:
- System configuration: CPU, kernel parameters...
- Cluster configuration
- Databases: size, access...
- Running queries, blocked queries...
- Indicators like Buffer Cache Hit Ratio, bloat...

This is not meant as a monitoring tool. It should hopefully help users to see if they have made any *big* mistakes in configuring the server. For anything it suggests, please understand the implications before changing your configuration.

TODO:
- improve the perl side of things, as the code is very baby perl
- improve comments
- test on more systems. Requires Time::Piece, can be installed on Fedora with yum install perl-core
- many checks to add on postgresql.conf parameters
