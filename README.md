##  описание : личный пэт проект. dataBase - образ postgres:13.3
   Есть таблица пользователя - пароль в hash.
   у пользователя есть своя анкета, которую он будет заполнять, так же на проекте реализован поиск пользователя по региону и городу. И есть отдельная таблица для комментариев. можно оставить комментарий и получить ответ на него ( 2 уровневый)
   - стек:  nest.js+TypeORM
   - Инструменты работы: dataGrid 

   Отношения: 
   - cities - ManyToOne - regions
   - profiles - OneToOne - users
   - comments - ManyToOne - users

<image src="/source/categories.png" alt="Выгрузка таблиц из dataGrid">

## Ниже реализация апи для работы с данными таблицами

<image src="/source/api.jpg" alt="restApi для работы с таблицами">