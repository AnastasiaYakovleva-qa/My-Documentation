# My-Documentation
## Пример написания баг-репорта


*[bug][web][прод]* Пропадает доп.опция  (например «без красного лука»), при изменении размера пиццы

*Описание:* При выборе пиццы и указании доп. опции «без лука», или «без оливок» и последующей смене размера пиццы — выбор доп. опций теряется.

*Шаги воспроизведения:*
 1. Зайти на https://dodopizza.ru
 2. Убрать у любой пиццы наполнители, например у пиццы с тунцом убрать красный лук
 3. Выбрать другой размер пиццы, например с 30 → 35 см

*Ожидаемый результат:* доп. опции сохраняются при смене размера пиццы*Актуальный результат:* доп. опции теряются

*Окружение:* Браузер Google Chrome Версия 100.0.4896.127 (Официальная сборка), (64 бит)

*Тестовые устройства:* ZenBook UX333FA_UX333FA Microsoft Windows [Version 10.0.19043.1645]

*Аналитика:* Если компания предоставляет инструменты для просмотра аналитики, то укажу какой % пользователей заэфектило

*Логи:* Если возможно приложу логи (например, в кибане или logcat если на мобилках)

*Скринкаст:* http://recordit.co/HOSMmDS9Td
