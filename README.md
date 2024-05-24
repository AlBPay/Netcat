# Alliance bank NetCat Payment module

## NetCat 5.8 + E-commerce
----
### Установка:

1. Создаем мерчанта в личном кабинете https://portal.albpay.io/mportal/#/
2. Копируем папку netcat в корень сайта
3. Выполняем содержание файла fondy.sql в командной строке SQL (NetCat -> Инструменты -> Командная строка SQL)
4. Далее заходим Настройки -> Интернет магазин -> Оплата -> Добавить
5. Заполняем Платежная система: Alliance bank онлайн платежи
6. Настройки -> Интернет магазин -> Прием платежей -> Выбираем Сайт -> Включаем метод оплаты -> Сохранить
    `merchant_id` – Идентификатор мерчанта
    `secret_key` – секретный ключ
    `delayed` – признак отложенного платежа (https://documentation.albpay.io/docs/page/20/)
    `lifetime` – время жизни счета.
    `success_url` – страница куда будет перенаправлен мерчант после оплаты