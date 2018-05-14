Pass the URL of the Oracle server with `URL` envvar and the file you want to run with `FILE` envvar:

```
$ docker run -e URL=<user>/<password>@//xxx.yyy.eu-west-1.rds.amazonaws.com:1521/ORCL -e FILE=file.sql -v $PWD/file.sql:/file.sql -ti sflyr/sqlplus
```
