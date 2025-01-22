# Krasykov_Konstantin_3-TID-3_WEB_lab_6
Шестая практика, создание бекенд сайта и подключение к фронтенд. По заданию требовалось создать студенческий учет
```
Сущность студента: ⦁ Id ⦁ Фамилия ⦁ Имя ⦁ Отчество ⦁ Возраст ⦁ Пол ⦁ Почта ⦁ Номер телефона ⦁ Группа ⦁ Форма обучения ⦁ Дата зачисления

Все доступные запросы:

/addStudentsM (POST) -
добавление с помощью JSON большое количество студентов единоразом

/addStudent (POST) -
добавление с помощью JSON одного студента единожды

/student/{id} (GET) -
поиск студента по студенчискому билету ( {id} - любое число. Пример - ( http://localhost:8080/student/1 ) )

/student?g=n (GET) -
поиск студентов по гендеру ( n - вместо него вписываем Мужской или Женский. Пример ( http://localhost:8080/student?g=Мужской ) )

/ageGreaterThan?age=n (GET) -
поиск студентов больше определённого возраста ( n- вместо него, любой возраст. Пример ( http://localhost:8080/ageGreaterThan?age=21 ) )

/getStudents (GET) -
выводит всех студенто, которые есть в базе данных (Пример ( http://localhost:8080/studentByGroup?group=3-ТИД-2 ) )

/studentByGroup?group=n (GET) -
поиск студентов по группе ( n - любая группа. Пример ( http://localhost:8080/studentByGroup?group=3-ТИД-2 ) )

/updateStudent/{id} (PATCH) -
редактирование информации студента ( {id} - любое число. Пример ( http:/localhost:8080//updateStudent/1 ) )

/deleteStudent/{id} (DELETE) -
удаление студента ( {id} - любое число. Пример ( http://localhost:8080/deleteStudent/1 ) )
```
