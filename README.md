### Выберете столбец из таблицы, где в любой из позиции есть far
```sql
SELECT TOP 1
FROM table
WHERE column
LIKE '%far%';
```
### Посчитать среднее значения в столбце, где значение больше 20
```sql
SELECT AVG(column)
FROM family
WHERE salary > 20;
```

### Обновите таблицу на значение, где id равно 3
```sql
UPDATE table 
SET column=value
WHERE id=3;
```
