REST — аббревиатура от Representational State Transfer / Передача Состояния Представления
REST — архитектурный стиль поверх HTTP.

URL + URN = URI
URL — адрес ресурса в сети
URN — идентификатор ресурса
URI — идентификатор ресурса в сети
# Принципы REST
## 1) Клиент-серверная модель
Во взаимодействии участвует двое: клиент (запрашивает сущности) и сервер (хранит и отдает сущности)

## 2) Отсутствие состояния 
На сервере не хранится никакой информации о прошлых запросах. Каждый запрос должен содержать всю информацию для его обработки

## 3) Кеширование
Для уменьшение нагрузки из-за повторяющихся одинаковых запросов. Может быть как на стороне сервера, так и на стороне клиента

## 4) Единообразие интерфейса
Запрос должен происходить по одинаковой структуре, а ответ в одинаковом формате

## 5) Система слоев / Многоуровневость
В системе клиент-сервер еще могут быть промежуточные слои. Например proxy сервер

Если система удовлетворяет этим принципам, то она RESTfull

RESTful не обязательно, но часто реализует все CRUD операции

