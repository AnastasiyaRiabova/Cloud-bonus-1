# Задание к занятию «Yandex Cloud Functions»

**Выполните задания.**

**Задание 1.**

Изучите инструкцию, как начать работать с [Yandex Cloud Functions](https://cloud.yandex.ru/docs/functions/).

**Задание 2.**

Используя Yandex Cloud Functions, реализуйте описанную бизнес-логику:   

Метод | URL | Действие | Комментарий
--- | --- | ---  | ---
`GET` | `/api/characters` | Получить всех персонажей | Получаем массив всех персонажей
`GET` | `/api/character?id=1` | Получить персонажа по **ID** | Получаем объект персонажа, если запись «не найдено», вернём **Code: 404** 

Структура объекта персонажа:
```json
{
    id: 1,
    name: "Имя персонажа",
    description: "описание...",
    modified: "2020-07-21",
    thumbnail: "http://...",
    comics: [
        {
            id: 1,
            name: "Spider-Man: 101 Ways to End the Clone Saga (1997) #1"
        }
    ]
}
```


**Задание 3** (необязательное).

* Изучите инструкции, как начать работать с инструментами [Managed Service for MongoDB](https://cloud.yandex.ru/docs/managed-mongodb/quickstart) и [Managed Service for PostgreSQL](https://cloud.yandex.ru/docs/managed-postgresql/quickstart?utm_source=console). 
* Выберите один из этих инструментов в качестве основного. 
* Создайте кластер выбранной БД и реализуйте хранение данных и персонажах в БД.

