# Модуль доставки Новой Почтой для Magento 2.3

Модуль поддерживает два вида доставок: Склад-Склад и Склад-Двери.
Поддерживает два языка, русский и украинский.

## Установка

Скопировать файлы модуля в папку `app/code/Yu/NovaPoshta`.

Выполнить команды в терминале:

```
php bin/magento module:enable Yu_NovaPoshta
php bin/magento setup:upgrade
```

Импортировать справочники городов и отделений Новой Почты

```
php bin/magento novaposhta:data:import
```


## Настройка

После установки необходимо получить ключ API на сайте Новой Почты в личном кабинете.
Как получить API ключ можно посмотреть здесь: https://www.youtube.com/watch?v=Gjc6vXUY1as

Ключ API и настройки модуля добавляются в разделе `Кофигурация - Продажа - Методы доставки`

![alt text](/docs/config.jpg "Configuration of Yu_NovaPoshta")

### Поддержка

Вопросы, пожелания можно писать на  
email: yuriy.akishin@gmail.com  
skype: yuriy-a76