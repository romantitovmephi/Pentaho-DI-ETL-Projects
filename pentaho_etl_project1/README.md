## Использовалась версия Pentaho DI Version 9.4. Корректно работает с версией Java 8 Update 121

`staging_orders.ktr` - трансформация по загрузке данных из файла Excel в базу данных

![staging](https://github.com/romantitovmephi/Pentaho-DI-ETL-Projects/blob/main/scr/staging.png)

![stg](https://github.com/romantitovmephi/Pentaho-DI-ETL-Projects/blob/main/scr/stg.png)

`dim_tables.ktr` - трансформация данных внутри базы данных

![dimension](https://github.com/romantitovmephi/Pentaho-DI-ETL-Projects/blob/main/scr/dimension.png)

![dw](https://github.com/romantitovmephi/Pentaho-DI-ETL-Projects/blob/main/scr/dw.png)

`job.kjb` - job, выполняющий всю последовательность трансформаций (оркестрирует data pipeline)

![job](https://github.com/romantitovmephi/Pentaho-DI-ETL-Projects/blob/main/scr/job.png)
