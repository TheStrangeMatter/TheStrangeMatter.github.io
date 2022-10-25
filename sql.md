# SQL запросы

1) SELECT count(\*) FROM information_schema.tables WHERE table_type="BASE TABLE" --- 10 таблиц
2) SELECT TABLE_NAME  FROM information_schema.tables WHERE table_type="BASE TABLE" --- 
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
3) SELECT count(\*) FROM users --- 261 пользователей
4) SELECT count(\*) FROM grades --- 2 оценки
5) SELECT * FROM users, grades WHERE users.user_id=grades.user_id --- Павел Сверчков получил 5 и 4
6) SELECT * FROM users WHERE name="Анастасия" - Я под 248 номером
