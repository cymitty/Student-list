# Задача про список студентов (student-list)
***Ссылка на задачу https://github.com/codedokode/pasta/blob/master/student-list.md***

**_Если есть предложения по любым улучшениям/упрощениям проекта - буду рад вашим pull request'ам_**

## О проекте:
Задача: **Создать сайт 'список студентов'**

Цель: **Изучить архитектуру MVC на примере приложения _Список студентов_**
### Страницы:
* Главная страница - список всех зарегестрированных студентов
* Страницы добавления/изменения данных о себе

### Функционал:
* Регистрация студента
* Изменение данных о себе(о студенте)
* Сортировка списка студентов по любому столбцу списка
* Поиск по любому столбцу списка

### Разные словечки непосредственно относящиеся к проекту
OOP, MVC pattern, PDO, TableDataGateway Pattern для работы с БД, dependency injection, git, Composer, Twitter bootstrap.

## Требования к установке проекта
**Используемые программы:**

PHP >= 5.3, mysql, composer

**Порядок установки:**

Создать БД. В корне проекта имеется дамп базы данных studentlist.sql который нужно импортировать в вами созданную БД.

В Config.ini ( директории `app/` ) вводим настройки БД.

Установите зависимости проекта: _composer install_

Настройте свой веб-сервер так чтобы корень сайта был в `public_html/` 

_**Проект готов к использованию**_

В проекте Студент - Abiturient.

Для заполнения базы данных случайными Абитуриентами можно использовать filldb.php . Используется библиотека https://github.com/fzaninotto/Faker 

Код контроллеров находится в входных скриптах (Контроллер index.php - public_html/index.php) 

**_Если есть предложения по любым улучшениям/упрощениям проекта - буду рад вашим pull request'ам_**