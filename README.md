## `pg_loader_docs`
Documentation for using [pg_loader](https://pgloader.readthedocs.io/en/latest/index.html)


### Mac Install

```bash
brew install pgloader
```

### sqlite -> postgresql

```bash
pgloader db.load 
```

... where `db_load` is

```
load database
     from sqlite:///Users/warren/code/python-things/db/main.sqlite
     into postgresql://root@127.0.0.1/things_db

with include drop, create tables, create indexes, reset sequences

set work_mem to '16MB', maintenance_work_mem to '512 MB';
```


