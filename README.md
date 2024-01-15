# Скрипт для установки приложений CarModApps для автомобилей Lixiang

## Установка

TODO

## Использование

```
Использование: installer.sh [options] [<команда>]

По-умолчанию выполняется update + install

Команды:
  vin: Отобразить VIN
  install: Запустить автоматическую установку приложений
  update: Загрузить приложения с сервера CarModApps
  delete: Удалить ВСЕ не системные приложения, включая CarModApps и пользовательские приложения
  clear: Удалить все приложения, кроме CarModApps и пользовательских приложений

 Общие опции:
  -h, --help: Показать это сообщение
  -v, --verbose: Выводить подробную информацию
  -f, --force: Принудительно установить приложения, даже если они уже установлены
  
Опции при запуске без команды:
  -d, Выполнить удаление ВСЕХ не системных приложений перед установкой
  -c, Выполнить удаление всех приложений, кроме CarModApps и пользовательских приложений

Для добавления своих приложений положите apk в папки:

   packages/custom/driver   Для экрана водителя
   packages/custom/copilot  Для экрана пассажира
   packages/custom/rear     Для заднего экрана

Кастомизация настроек (для продвинутых пользователей):

  1. Создайте файл user_settings.sh
  2. Добавьте в него переопределение переменных
     Пример добавления установки Angry birds из CarModApps на все экраны:
        APPS_ALL_SCREENS+=("com.rovio.angrybirds")
```

