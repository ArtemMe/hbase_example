# hbase_example

https://hub.docker.com/r/pierrezemb/hbase-docker/

### Заметки

Чтбы нормально работал zookeeper нужно настроить файки hosts
без него не работает.

Что из себя представляет таблицы в hbase:

![alt text](https://habrastorage.org/getpro/habr/post_images/72f/db4/418/72fdb44187d02c8affdc9740eb691115.png)

rowkey - ключ
Доступ к данным можно представить как:
<table, RowKey, Column Family, Column, timestamp> -> Value

Веб консоль БД: http://hbase-docker:16010/master-status
