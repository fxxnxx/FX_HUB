# FX HUB

Обход блокировок, прокси для Telegram и настройка DNS для Windows.

[Скачать последнюю версию](https://github.com/fxxnxx/FX_HUB/releases/latest) (файл `FX_HUB-…-win64.zip`)

## Возможности

- Обход блокировок на стратегиях zapret от Flowseal. Кнопка «Проверить все» перебирает стратегии и включает рабочую с самым низким пингом.
- Прокси для Telegram (TG WS Proxy). Включается вместе с обходом.
- DNS: Xbox DNS и свои серверы. Адреса Xbox DNS обновляются с их сайта, при сбое включается резервный DNS.
- Автозапуск с Windows.
- Обновления. Программа сообщает о новой версии и обновляется по кнопке.

## Установка

1. Скачайте архив из [Releases](https://github.com/fxxnxx/FX_HUB/releases/latest) и распакуйте в короткий путь, например `C:\FX_HUB`.
2. Запустите `FX_HUB.exe` и разрешите запуск от администратора.
3. Нажмите кнопку включения на главной.

Обход работает через драйвер WinDivert, на него иногда срабатывают антивирусы. Если антивирус удаляет файлы, добавьте папку FX_HUB в исключения.

## Контакты

Сайт: [balbasov.ru](https://balbasov.ru)

Discord: [написать](https://discordapp.com/users/353830271298043905)

## Используемые проекты

- [zapret-discord-youtube](https://github.com/Flowseal/zapret-discord-youtube), Flowseal, MIT
- [zapret](https://github.com/bol-van/zapret), bol-van, MIT
- [WinDivert](https://github.com/basil00/WinDivert), basil00, LGPLv3
- [TG WS Proxy](https://github.com/Flowseal/tg-ws-proxy), Flowseal, MIT
- Qt for Python, LGPLv3

Тексты лицензий лежат в папке `licenses` внутри архива.
