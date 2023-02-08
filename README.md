# Transfer Nightscout data to LibreView
Transfer your diabetes data from Nightscout to LibreView.

## Для начала нужно установить:
- git
- nodejs

## Первый запуск

В консоли выполняем команды:
```
git clone https://github.com/mo211073bkp/mynightscout-librelink-up
cd mynightscout-librelink-up
sudo apt install npm
npm start
```

## Последующее использование

В консоли выполняем команды:
```
cd mynightscout-librelink-up
npm start
```

## Todo
- many many testing!
- better error handling
- clean up entry point
- clean up user input
- add frequent unscheduledContinuousGlucoseEntries
- add notes from libreview
- add basal insulin?!?
- different libreview api endpoints
