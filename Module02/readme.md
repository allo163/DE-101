### Установка БД
 - Установил БД PostgreSQL
 - Установил IDE DBeaver, соединение с утановленной БД PG
 - На удаленном сервере AWS Lightsail создана виртуальная БД, соединена с DBeaver
---------------------------------------
### SQL запросы
 - Из excel-файла [Sample-superstore](https://github.com/allo163/DE-101/blob/main/Module02/Sample%20-%20Superstore.xls) сформировал путем SQLizer 3 sql-файла:
   peoples.sql, orders.sql, returns.sql
----------------------------------------
### Загрузка данных в БД
 - В БД загрузил "сырые" данные в staging слой из файла [stg.orders.sql](https://github.com/allo163/DE-101/blob/main/Module02/stg.orders.sql)
-------------------------------------
### Нарисовать модель данных в [SQLdbm](https://sqldbm.com/)
 - Сформировал и нарисовал в SQLdbm *Концептуальную модель БД* ![](https://github.com/allo163/DE-101/blob/main/Module02/concept%20model.jpg "Концептуальная модель")
 - Сформировал и нарисовал в SQLdbm *Логическую и физическую модель БД* ![](https://github.com/allo163/DE-101/blob/main/Module02/logical%20(%2Bphisical)%20model.jpg "физическая модель")
 - Создал SQL файл на основе полученной модели [from_stg_to_dw](https://github.com/allo163/DE-101/blob/main/Module02/from_stg_to_dw.sql) для создания dimention слоя БД и заполнил данными из таблиц oreders, people, returns.
---------------------------------
### Нарисовать графики в Google Sheets
### Нарисовать графики в KlipFolio
