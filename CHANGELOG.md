# Change Log
Все заметные изменения в проекте будут описаны в этом файле

## [2.2.2] - 12-11-2016
### Добавлено
- Новый метод executes для мультивызова методов
- Метод gifts.send
- Прокси

### Исправления
- Отрефакторен код в некоторых местах
- Обновлены зависимости
- Обновлена версия API

## [2.2.0] - 18-10-2016
### Добавлено
- Начался ввестись Change Log
- Добавлена обработка longpoll (подарков, переводов, стикеров)
- Новые методы «Подписка на сообщения сообщества»
- Добавлены методы для работы с рекламным кабинетом

### Исправления
- Теперь отправляются большие запросы
- Теперь longpoll не будет падать от (ETIMEDOUT, ENOENT)
- Небольшие оптимизации в модуле
- Обновлена версия API