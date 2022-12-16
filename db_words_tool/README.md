# Пополняемый список слов в изучении

*Автор - **[Волков Максим](https://t.me/dvcvms)***

## Описание микросервиса:

* Микросервис организует работу с базой данной. 
Помогает пользователям построить эффективный процесс изучения новых слов,
лучше ориентироваться при обучении. 
Позволяет изучать те слова, которые нуждаются во внимании.
* Осуществлена поддержка многопользовательского использования микросервиса. 
Это обеспечено благодаря общей таблицы с идентификатором пользователя TENANT_ID,
что является уникальным логином пользователя, заданного при регистрации.


## Микросервис предоставляет возможность:

* Добавить новое слово
* Удалить заданное слово
* Проверить наличие слова
* Изменить состояние признака слова
* Получить список слов по признаку

## Как пользоваться?

Для работы с микросервисом необходимо подключить базу данных.
В классе Test используется H2, где также предоставлены варианты использования
функционала микросервиса.