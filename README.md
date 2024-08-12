
#Пример команд для использования в консоли __Database SQL CLI__
---
1. ```sql
2. SELECT name FROM sqlite_master WHERE type='table' AND name NOT LIKE 'sqlite_%'
3. ``` вывести список названий всех таблиц

