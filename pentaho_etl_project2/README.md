`job_download_file.kjb` - скачивает файл через HTTP или Shell (указать путь до `import.sh`)

![download](https://github.com/romantitovmephi/Pentaho-DI-ETL-Projects/blob/main/pentaho_etl_project2/screens/dwnld.png)

`merge_transformation.ktr` - объединяет данные из трех таблиц в одну, сохраняет в `file-general.csv`

![merge](https://github.com/romantitovmephi/Pentaho-DI-ETL-Projects/blob/main/pentaho_etl_project2/screens/mrg.png)

`transformation_for_task.ktr` - разбивает данные на разные форматы:
1) инфо по продуктам в JSON формате (папка products)
2) инфо о возвратах в XML (папка returns)
3) инфо о заказах по регионам (папка orders):
  - CENTRAL (XLS)
  - WEST (CSV)
  - SOUTH (CSV in ZIP)
  - EAST (DAT)

![tft](https://github.com/romantitovmephi/Pentaho-DI-ETL-Projects/blob/main/pentaho_etl_project2/screens/tft.png)

`final_job.kjb` - выполняет всю последовательность трансформаций

![final](https://github.com/romantitovmephi/Pentaho-DI-ETL-Projects/blob/main/pentaho_etl_project2/screens/final.png)


P.S. перед запуском final_job и не только проверить: Edit - Set Environment Variables: HOME и WORKFOLDER - пути до них, соответственно пути к папкам temp и pentaho_etl_jobs2
