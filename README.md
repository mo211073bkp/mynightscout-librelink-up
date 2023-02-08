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
В ходе выполнения скрипта Вам необходимо ввсети:
```
nightscoutUrl в формате "https://mysite.ru"
nightscoutToken":"075c777ac34218c79c94c0d7089052d394775e88e" - это преобразованный в SHA1 с помощью сайта http://www.sha1-online.com/ Ваш API secret.
libreUsername":"qwertysdp@gmail.com" - Ваш E-mail, указанный при регистрации на сайте LibreView.
librePassword":"koala_54" - Ваш пароль, указанный при регистрации на сайте LibreView.
libreDevice":"3C9F71FD-7F06-3EB1-6F34-1ABE36B5A980" - можно оставить поле пустым.
```
