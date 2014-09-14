pg_doctor
=========

A script to check the "health" of your PostgreSQL server. What should be checked:
- System configuration
- Cluster configuration
- Databases: size, access...
- Running queries
- Indicators like Buffer Cache Hit Ratio, bloat...

This is not meant as a monitoring tool. It should hopefully help users to see if they have made any *big* mistakes in configuring the server.
