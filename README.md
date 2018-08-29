# Google Cloud SQL Proxy Service

https://cloud.google.com/sql/docs/postgres/connect-external-app

## Installing

```sh
curl -sO https://raw.githubusercontent.com/tuanngo/cloudsql-proxy/master/install && bash install
```


## Running Cloud SQL Proxy
As with any init.d service, you can simply use the "service" command to start, stop or restart cloud_sql_proxy:
```sh
$ service cloudsql start
$ service cloudsql stop
$ service cloudsql restart
```

## Cloud SQL Proxy Logging
The service will log all the output from cloud_sql_proxy to /var/log/cloudsql.log.

### NOTE 
We're not responsible for what this script does to your server.  Use it at your own risk.

### "Thank You" to...
https://github.com/openach/cloudsql-service






