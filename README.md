# ТЗ по сайту
## Варианты кейсов
1. Сайт компании/мероприятия
2. Web-приложение
## Требования к сайту компании/мероприятия
* Сайт должен работать как клиент-серверное приложение, а не монолит;
* Запуск клиентской части не должен требовать наличия фреймворков на VM;
* Клиентская часть должна содержать:
  * Навигацию;
  * Несколько секций с информацией и фотографиями;
  * Ссылки на соц.сети;
  * Форму для подачи заявки/обратной связи и т.п (2-4 поля, согласие, кнопочка).
* Серверная часть должна иметь следующий функционал:
  * Принятие и обработка запросов от клиентской формы;
  * Возможность возврата всех заявок.
* Обязательно продумайте, каким образом будут отображаться и редактироваться заявки администратором сайта.
## Требования к Web-приложению:
* Приложение может быть как монолитом, так и основываться на клиент-серверном взаимодействии.
* Приложение должно иметь состояние, которое в процессе работы будет изменяться пользователем. Только в таком случае сайт является приложением.
* У приложения должно быть меню с функциональными кнопками, скрывающееся в мобильной версии и всегда показывающееся в остальных.
* Доступные html препроцессоры:
  * pug
  * ejs
## Общие требования:
* Проект должен иметь минимум 3 дизайна адаптивныйх под < 400px, < 700px, < 1200px;
* Список серверных фреймворков, допущенных к использованию:
  * Express - за разработку 12 баллов, за защиту 8 баллов;
  * Socket (C++/ Java) - за разработку 8 баллов, за защиту 12 баллов.
  * Socket.IO/ WebSockets - за разработку 6 баллов, за защиту 14 баллов.
* Список технологий и frontend-фреймворков, допущенных к использованию:
  * React - за разработку 6 баллов, за защиту 14 баллов;
  * Html/js - за разработку 12 баллов, за защиту 8 балла;
  * Bootstrap - за разработку 8 баллов, за защиту 12 баллов.
* Разрешенные технологии, не влияющие на итоговое кол-во баллов:
  * JQuery/Fancybox;
  * Sass;
  * nedb;
  * Redis;
  * Wow.js;
  * PostgreSQL;
  * Утилиты для парсинга запросов;
  * Утилиты для работы с CORS;
  * moment.js
### Правила выполнения:
* Технологии, не указанные в документе следует утвердить заранее до 7.11;
* Разработчики серверной и клиентской части защищиает свои зоны ответственности и набирают соответствующие баллы. TeamLead получает усредненное кол-во баллов по команде;
* Проект команды должны быть подготовленны к запуску на преподавательском компьютере;
* Проект команды должен сопровождаться презентацией для выступления и демонстрации концепции проекта;

### Правила оценки
* 5 - 16 баллов
* 4 - 14 баллов
* 3 - 10 баллов
