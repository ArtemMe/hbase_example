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


Отличный докер контейнер с hbase и всеми приблудами: https://github.com/dajobe/hbase-docker    
Консоль:
hbase shell


Для запуска на винде нужно не забыть прописать роут иначе не достучишься:

route /P add 172.0.0.0 MASK 255.0.0.0 10.0.75.2


https://stackoverflow.com/questions/41851066/exception-in-thread-main-java-lang-unsatisfiedlinkerror-org-apache-hadoop-io      
https://stackoverflow.com/questions/35652665/java-io-ioexception-could-not-locate-executable-null-bin-winutils-exe-in-the-ha
