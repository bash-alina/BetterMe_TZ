# BetterMe_TZ
## TC Post /user - Create user:
1. 
| Id  | Name                                                                   | Steps                                                                                           | Method | URL                                 | Headers | Request                                | ER Status Code | ER Response                             | Comment                                                               |
| :-: | ---------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------ | ----------------------------------- | ------- | -------------------------------------- | -------------- | --------------------------------------- | --------------------------------------------------------------------- |
|  1  | Проверить, что можно зарегистрировать пользователя в системе           | 1. Отправить запрос с вадидными данными. 2. Проверить, что все указанные данные записалисьв БД. | POST   | https://petstore.swagger.io/v2/user |         | [create user](requests.md#create-user) | 200            | [create user](responses.md#create-user) |                                                                       |
|  2  | Проверить, что поле *id* обязательно                                   |                                                                                                 | POST   | https://petstore.swagger.io/v2/user |         | [id required](requests.md#id-required) | 400            | [id required](responses.md#id-required) |                                                                       |
|  3  | Проверить, что поле *username* обязательно                             |                                                                                                 |        |                                     |         |                                        |                |                                         | Значение *usename* обязательно. Так как это значение ключевое для API |
|  4  | Проверить, что поле *firstName* необязательно                          |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
|  5  | Проверить, что поле *lastName* необязательно                           |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
|  6  | Проверить, что поле *email* необязательно                              |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
|  7  | Проверить, что поле *password* обязательно                             |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
|  8  | Проверить, что поле *phone* обязательно                                |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
|  9  | Проверить, что поле *userStatus* обязательно                           |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 10  | Проверить, что поле *username* уникально                               |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 11  | Проверить, что поле *id* уникально                                     |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 12  | проверить, что поле  *phone* уникально                                 |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 13  | Проверить, что у поля *id* тип *int*. Ввести символ                    |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 14  | Проверить, что у поля *id* тип *int*. Ввести буквенный символ          |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 15  | Проверить, что поля у *userStatus* тип *int*.  Ввести символ           |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 16  | Проверить, что у поля *userStatus* тип *int*. Ввести буквенный символ  |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 17  | Проверить, что для  запроса *Create user* нельзя создать массив        |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 18  | Проверить, что ситема не реагирует на добавление нового поля в объекте |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 19  |                                                                        |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
| 20  |                                                                        |                                                                                                 |        |                                     |         |                                        |                |                                         |                                                                       |
