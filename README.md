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
