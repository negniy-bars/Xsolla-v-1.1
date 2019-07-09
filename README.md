# Xsolla-v-1.1

### Рефакторинг документации Mermaid
### [Link](https://github.com/knsv/mermaid/issues/642)

**Список задач:**

- Понять, что это за проект
- Понять, какие issues можно редачить и нужно редачить

# Тут будет нумерация задач по степени важности
1. First
2. Second
+ Third
  + third.first
  + third.second 
  + third.third
  
## Таблица с названиями статей и статусом готовности

|Задача|Статус|
------|------
Первая задача|Ожидает разбора
Вторая задача|Ожидает разбора
Третья задача|Готова к взятию в работу

### Немножко кода

`print('hello, world!)`


### Описание метода API для получения списка продуктов по ID проекта

2. Описание метода 

Метод позволяет получить список продуктов в нужном проекте, обращение к проекту происходит через id проекта

3. Параметры запроса

имя параметра `project_id` 
тип параметра integer 
описание параметра ID проекта
параметр передается в GEt запрос
Для получения значения  project_id необходимо перейти туда-то

Пример GET-запроса


4. Параметры ответа

Полученный ответ в виде json-файла
в формате:
Продукт (параметр) - статус подключенности к текущему проекту (формат string)

5. Пример кода 

Пример запроса
`GET https://api.example.com/products/{project_id}` 
`Headers:
Authorization: Basic <your_authorization_basic_key>`

Пример ответа:

`{
	Product1: connected, 
	Product2: disconnected
}`
