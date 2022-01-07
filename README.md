# Sql Server Local Database Manager

This is a script that can help developers create and manage a series of sql server databases on their local machines, using docker containers and volumes.
This tool should only be used for local development.

## Available commands

* ```db create <db-name>```: Create a new database configuration.

* ```db update <db-name>```: Update an existing database configuration.

* ```db remove <db-name>```: Remove an existing database configuration.

* ```db start <db-name>```: Start a database with given configuration.

* ```db stop <db-name>```: Stop a database.

* ```db list```: List all available databases.
