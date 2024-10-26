Запускается с помощью команды docker-compose up.

Метрики:

http://localhost:8080/metrics

Метрики:
request_duration
requests_total
get_cache_duration
get_external_api_duration

Авторизация реализована через **cookies**: работает и в swagger и в postman. Достаточно проставить корреткный логин и пароль - и токен сам проставиться в нужное место.

Готовый пользователь для авторизации:
Логин: flip
Пароль: flop