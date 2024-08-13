
#__Database SQL CLI__
---
1. ```SELECT name FROM sqlite_master WHERE type='table' AND name NOT LIKE 'sqlite_%'``` вывести список названий всех таблиц
2. ```SELECT * FROM {TableName}``` вывести содержимое таблицы
3. ```UPDATE Users SET Role = '4' WHERE Login = 'zorkincc';``` Обновить роль ползователя в таблице Users для пользователя со значением логин 'zorkincc'
4. ```EXECUTE_NO_SQL FixDepartmentCells``` Обновить значения "Кафедра" и "КафедраОП" для строк таблицы FileAction где они NULL согласно значению FileName
5. ```EXECUTE_NO_SQL ImportDatabase``` Вывести меню импорта данных
6. ```EXECUTE_NO_SQL CheckHealth``` Проверить текущее состояние базы данных
   

