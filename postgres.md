# POSTGRES

	* sudo apt-get update
	* sudo apt-get install postgresql postgresql-contrib
	* sudo su postgres
	* createuser --interactive -P
	* createdb <db_name> --owner <role_name>

## for creating HSTORE  in postgres

	*  psql <db_name> -c "create extension hstore;"


## get backup

	* pg_dump <db_name> > file_name.dump

## to restore

	* psql <db_name> < file_name.dump
