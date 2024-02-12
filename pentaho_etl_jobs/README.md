`job_download_file.kjb` - скачивает файл через HTTP или Shell (указать путь до `import.sh`)
![download]()

`merge_transformation.ktr` - объединяет данные из трех таблиц в одну, сохраняет в `file-general.csv`
![merge]()

`transformation_for_task.ktr` - разбивает данные на разные форматы:
1) инфо по продуктам в JSON формате (папка products)
2) инфо о возвратах в XML (папка returns)
3) инфо о заказах по регионам (папка orders):
  - CENTRAL (XLS)
  - WEST (CSV)
  - SOUTH (CSV in ZIP)
  - EAST (DAT)

![tft]()

`final_job.kjb` - выполняет всю последовательность трансформаций
