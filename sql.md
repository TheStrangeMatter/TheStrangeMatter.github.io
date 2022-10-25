# SQL запросы

## 1
`SELECT count(*) FROM information_schema.tables WHERE table_type="BASE TABLE"` 
Выбрать количество элементов из information_schema.tables (файла с таблицами), которые являются таблицами, чей тип - "BASE TABLE"

10 таблиц
## 2 
`SELECT TABLE_NAME FROM information_schema.tables WHERE table_type="BASE TABLE"` 
Выбрать имена таблиц из information_schema.tables, которые являются таблицами, чей тип - "BASE TABLE"

- ('movies',)
- ('movi',)
- ('mov',)
- ('class',)
- ('grades',)
- ('users',)
- ('Kukina',)
- ('common',)
- ('my_table',)
- ('TIMURIUS',)
## 3 
`SELECT count(*) FROM users`
Выбрать количество элементов из таблицы users 

261 пользователей

## 4 
`SELECT count(*) FROM grades`
Выбрать количество элементов из таблицы grades

2 оценки
## 5 
`SELECT * FROM users, grades WHERE users.user_id=grades.user_id`
Выбрать элементы из таблиц users и grades, чьи идентификаторы совпадают. Таким образом можно найти, какие оценки к каким ученикам привязанам.

Павел Сверчков получил 5 и 4
## 6
`SELECT * FROM users WHERE name="Анастасия"
Выбрать элементы из таблицы users, в которых строчка name равняется "Анастасия". Таким образом можно найти всех учеников с именем Анастасия

Я под 248 номером
