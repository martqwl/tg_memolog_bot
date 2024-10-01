# Бот-мемолог The Rock

Телеграм-бот, который отправляет рандомные мемы с Реддита, основываясь на некоторых параметрах,
введенных пользователем.

## Описание

Проект представляет собой бота, который предлагает на
выбор несколько категорий(hot, new, rising, top) и фильтрует мемы по времени(week, hour, year,
all, day, month).
В зависимости от выбора пользователя бот отвечает различно, сортируя мемы по введенным параметрам и
находя рандомный мем в соответствии с ними.

## Инструкция по использованию

- Начало
    - Найдите бота в Telegram: @therrrockbot
    - Запустите бота командой /start.
    - Для просмотра функций бота напишите команду help.
- Параметры запроса
    - В одной строчке с командой /meme необходимо ввести некоторые параметры для запроса
    - Первый параметр: ключевое слово. Название игры, животное, чье-либо имя и т.д.
    - Второй параметр: категория. Новый, наиболее часто просматриваемый и т.д.
    - Третий и последний параметр: время. Мемы, выложенные на этой неделе, в этом году, за последний час и т.д
- Для тестировщиков
    - Для тестировщиков в боте создан специальный режим отладки.
    - По команде /debug бот отправляет лог-файл
    - По команде /debug_mode_on бот включает режим отладки, в котором бот выводит все логи.
    - По команде /debbug_mode_in бот выключает режим отладки и возвращается в привычный режим.
- Ежедневный мем
    - После ввода команды КОТОРОЙ ПОКА ЧТО НЕТ пользователю предлагается задать время, в которое он будет
получать мемы каждый день
    - По команде /daily_memes_stop пользователь отписывается от ежедневной рассылки мемов.
- Запланированный мем
    - По команде /planned_meme пользователь может установить время, в которое хочет получить случайный мем.


## Контакты

Для связи с разработчиками можно использовать следующие контакты:

- Ярослав
    - [Telegram](https://t.me/Pl1nTuS32)
    - [Почта](farev752@gmail.com)
