# PHP Connection with Postgres database
#### Prerequisites

1. WampServer
2. PgAdmin

#### 1. Enable PDO in Php.ini file

Remove semicolon (;) from these two lines from Php.ini files. You have to remove from PHP folder and also from Apache folder. 

```
extension=pdo_pgsql
extension=pgsql
```

![This is an image](/phpini.PNG)


![This is an image](/pdo_extension.PNG)

#### 2. Enable Pgsql in WampServer

![This is an image](/pgsql.png)
