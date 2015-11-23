# module-drupal-commerce

Модуль интеграции интернет-магазинов [e-Commerce](https://www.drupal.org/project/ecommerce) и [Commerce Kickstart](https://www.drupal.org/project/commerce_kickstart) с платежной системой [PayBox](http://paybox.kz).

### Инструкция

Для работы модуля необходимо выполнить следующие шаги:

##### 1. Заключить договор с PayBox

Заполнить форму заявки на сайте [PayBox](http://paybox.kz) для получения доступа к личному кабинету PayBox.

##### 2. Установить и настроить модуль модуль 

1. Скопировать папку из архива в папку *modules*.
2. Выбрать раздел Store &rarr; Configuration &rarr; Payment Methods.
3. Выбрать метод PayBox.
4. В настройках платежной системы заполнить поля данными из [личного кабинета PayBox](https://www.paybox.kz/admin/merchants.php).
4. Настроить способ оплаты.

---

Работа модуля протестирована на Drupal версии 7.3.1 и Commerce версии 1.10, Commerce KickStart версии 2.19.
