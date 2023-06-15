## Задание

Имеется web приложение (интернет магазин) которое состоит из следующих компонентов:
- Каfka
- Backend приложение
- Сервер БД MySQL
- Frontend приложение (SPA)

Описать процесс покупки товара (от корзины пользователя до момента оплаты и получения товара).

Для совершения покупок пользователи авторизуются.

У них есть личный кабинет где они могут посмотреть список купленных товаров.

Для обмена данных между клиентом и сервером, как мы вчера уточнили, используется REST.

Допустим мы хотим расширить функционал данного магазина таким образом:

- Если пользователь выбирает товар для покупки а товара нет на складе мы должны давать ему возможность для подписки на событие поступления товара на склад.
- По факту поступления товара на склад пользователь должен получить уведомление в личном кабинете.
- После того как уведомление будет прочитано его статус должен переходить на прочитано (read).
- У пользователя должно быть список своих уведомлений.

Требуется системный анализ для реализации данного функционала и по его итогам подготовить FS задачу для разработчика.

PS. Нужно подчеркнуть и описать все необходимые и важные процессы как мы вчера обсуждали во время собеседования.