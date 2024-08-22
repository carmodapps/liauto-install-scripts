# Скрипт для установки приложений CarModApps

- Сайт: https://carmodapps.com
- Группа в Telegram: https://t.me/carmodapps

## Требования

- Операционная система Mac OS X или Linux

## Установка

- Скачайте и распакуйте архив с репозиторием:
[liauto-install-scripts-master.zip](https://github.com/carmodapps/liauto-install-scripts/archive/master.zip)

## Быстрый старт

- Подсоедините USB разъемы переднего и заднего экранов(при наличии) к компьютеру.
  (Если у вас нет двух кабелей/портов - то можете подсоединить экраны по очереди) 
- Запустите `installer.sh -d`.

В результате будут выполнены следующие действия:
- Скачаны последние версии приложений с сервера CarModApps
- Удалены все сторонние не системные приложения (Также будут удалены китайские развлекательные приложения, но вы можете поставить их обратно через китайский магазин)
- Установлены приложения CarModApps на все подключенные экраны.


## Использование

Запустите `installer.sh -h` для получения справки по использованию:

```
Использование: installer.sh [options] [<команда>]

По-умолчанию выполняется update + install

Команды:
  vin: Отобразить VIN
  install: Запустить автоматическую установку приложений
  update: Загрузить приложения с сервера CarModApps
  delete: Удалить ВСЕ не системные приложения, включая CarModApps и пользовательские приложения

 Общие опции:
  -h, --help: Показать это сообщение
  -v, --verbose: Выводить подробную информацию
  -f, --force: Принудительно установить приложения, даже если они уже установлены

Опции при запуске без команды:
  -d, Выполнить удаление ВСЕХ не системных приложений перед установкой

Кастомизация настроек (для продвинутых пользователей):

  1. Создайте файл config.sh
  2. Добавьте в него переопределение переменных

  Пример файла можно посмотреть в config.sh.example
  
EOF
```
