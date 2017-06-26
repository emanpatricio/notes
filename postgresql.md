* change user to postgres
$ sudo -i -u postgres 
$ psql template1


* in postgressql console
CREATE USER tester WITH PASSWORD 'test_password';
template1=# GRANT ALL PRIVILEGES ON DATABASE "test_database" to tester;
template1=# \q
