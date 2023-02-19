# Домашнее задание к занятию 12.2. «Работа с данными (DDL/DML)» - `Виноградова Татьяна`

---

### Задание 1
1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

1.2. Создайте учётную запись sys_temp.

1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

![image](https://user-images.githubusercontent.com/103531664/219947079-f64d5804-eec2-4268-af76-6047a8abfba1.png)

1.4. Дайте все права для пользователя sys_temp.

![image](https://user-images.githubusercontent.com/103531664/219947104-d32c88a0-626e-437d-965c-2e8573946e69.png)

1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

![image](https://user-images.githubusercontent.com/103531664/219947129-1163dc74-d74c-411b-b8e6-181939cac43b.png)

1.6. Переподключитесь к базе данных от имени sys_temp. Для смены типа аутентификации с sha2 используйте запрос:
```ALTER USER ‘sys_temp’@’localhost’ IDENTIFIED WITH mysql_native_password BY '12345';```

![image](https://user-images.githubusercontent.com/103531664/219947177-e07dc63b-57ad-4dcf-b609-992c30037e75.png)

![image](https://user-images.githubusercontent.com/103531664/219947144-f2c45a4a-09bf-4d69-8726-39e159fdfcc9.png)

1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.
1.7. Восстановите дамп в базу данных.

![image](https://user-images.githubusercontent.com/103531664/219947191-78f158b0-7561-480c-b034-65471b6a7af9.png)

1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. 
При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

![image](https://user-images.githubusercontent.com/103531664/219947251-3f1069e1-0b6d-439b-b0de-da4e2f9964ae.png)

---
### Задание 2

Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца:
в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц.

![image](https://user-images.githubusercontent.com/103531664/219947373-2cb627d9-ed64-483c-ad8e-55ebd9489d7d.png)


---

### Задание 3

3.1. Уберите у пользователя sys_temp права на внесение, изменение и удаление данных из базы sakila.

![image](https://user-images.githubusercontent.com/103531664/219948732-51bac659-3292-4222-bcb0-bea11938454a.png)


```
