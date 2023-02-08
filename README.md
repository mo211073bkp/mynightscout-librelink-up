# Передача (в ручном режиме) данных из Nightscout в LibreView.

## Для начала нужно установить:
- git:
```
sudo apt update
sudo apt install git
Проверяем, что GIT встал: git version
```
- nodejs
```
sudo apt update
sudo apt install nodejs
Проверяем, что Nodejs встал: nodejs -v
```

Делаем клон из репозитория:
```
git clone https://github.com/mo211073bkp/mynightscout-librelink-up
```

Переходим в папку клона и устанавливаем npm:
```
cd mynightscout-librelink-up
sudo apt install npm
```


## Теперь всё готово к использованию, если Вы не в каталоге, то нужно в него перейти:

В консоли выполняем команды:
```
cd mynightscout-librelink-up
npm start
```
В ходе выполнения скрипта Вам необходимо ввести:
```
nightscout url: в формате "https://mysite.ru"
nightscout token: "075c777ac34218c79c94c0d7089052d394775e88e" - это преобразованный в SHA1 с помощью сайта http://www.sha1-online.com/ Ваш API secret.
libreview username: "qwertysdp@gmail.com" - Ваш E-mail, указанный при регистрации на сайте LibreView.
libreview password: "koala_54" - Ваш пароль, указанный при регистрации на сайте LibreView.
the year you want to transfer to libreview:  2023 данные какого года передаем
the month you want to transfer to libreview:  1 указываем порядковый номер месяца, за который передаем данные
if you have problems with your transfer, recreate your device id: - можно оставить поле пустым.
```
