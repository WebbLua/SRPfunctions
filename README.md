## SRPfunctions
Многофункциональный скрипт-хелпер с автообновлением для игроков проекта Samp-RP 
- Автор: Cody_Webb | Telegram: @Imykhailovich (для предложений по разработке и фиксам)

## Зависимости
- [samp.events](https://www.blast.hk/threads/14624/)
- [imgui](https://www.blast.hk/threads/19292/)
- [imgui_addons](https://www.blast.hk/threads/27544/)
- vkeys
- [rkeys](https://www.blast.hk/threads/27488/)
- ffi
- encoding

## Скачать скрипт и все необходимые библиотеки
-   [SRPfunctions.lua](https://drive.google.com/file/d/1-gtuVExgKkQeWfSW0HYzx-xocGLldeyg/view?usp=sharing)
-   [Папка lib(перекинуть в moonloader)](https://drive.google.com/file/d/1iTq3fTYjjfX5agpbuz0cGzjzEbH3nBzQ/view?usp=sharing)
-   [CLEO 4](https://cleo.li)
-   [SAMPFUNCS v5.4.1](https://www.blast.hk/threads/17/)
-   [Moonloader v026.5](https://www.blast.hk/threads/13305/)

## Установка скрипта

- Установить библиотеки из пункта Зависимости в корневую папку игры
- Переместить папку "lib" в папку moonloader корневой папки игры
- Переместить файл скрипта "SRPfunctions.lua" в папку moonloader корневой папки игры

## Функции

## Автоматические
- Починка у механика
- Заправка у механика
- Заправка на АЗС (с ограничением цены)
- Покупка канистры (с ограничением цены по АЗС)
- Заправка транспорта канистрой (если закончилось топливо)
- Окрашивание ников в чате профсоюза в цвета клистов
- Окрашивание ников в чате организации в цвета клистов
- Оповещение о выходе из игры в зоне прорисовки
- Оповещение об употреблении психохила в зоне прорисовки
- Автологин на сервере (пароль сохраняется в конфиге и никуда более)
- Автоаренда транспорта (с ограничением цены)
- Помощник для ограбления домов (автоматически выносится награбленное из дома и заходит обратно)
- Автоприём нАрКо при ломке (можно ограничить работу функции если вдруг на экране будут копы)
- Автоответчик на спам-СМС 
- Узнать когда слетит дом/квартира (+ /whenhouse)
![ ](https://i.imgur.com/uFuPvDh.png)	   
	   
## На клавиши/команды
- Контекстная клавиша (специальный единичный биндер, который отправляет нужное сообщение в той или инной ситуации:
			 1. Починка авто при поломке;  2. Репорт на игрока за DM; 3. Вызов докторов в вашу больницу;
			 4. Приветствие клиента такси; 5. Согласие для поездки;   6. Красивое прощание с клиентом.
			 7. Сказать 'Садись' клиенту по вызову
			 Функция работает только в случае включённой одноименной функции в разделе Overlay (п.7)
- Употребить нАрКо
- Сменить клист (переключатель клиста с /clist 0 на вами выбранный клист)
- Зайти в дом (если вы грабите дома, то скрипт сначала наденет балаклаву, далее той же клавишей вскроет дом)
- Открыть/закрыть транспорт (/lock)
- Автоматически зажать клавишу бега
- Быстрое меню биндера
- Выкинуть игроков из транспорта (если зажать то можно будет выкинуть конкретного) 
![ ](https://i.imgur.com/4rt27lt.png)	   
	   
## Overlay
- Отображение системной (не серверной!) даты и времени на экране
- Отображение вашего ника а ID'a в цвете клиста на экране
- Отображение вашего пинга на экране
- Отображение оставшегося времени cooldown употребления нАрКо
- Отображение таймеров до начала мероприятий (гонки, дерби, кальмар, пейнтбол)
- Отображение количества игроков в зоне прорисовки
- Отображение статуса контекстной клавиши в данное время (должно быть обязательно включено для работы)
- Отображение улучшенного вида сквада: 
1. Показывает количество состава 
2. Наличие игрока в прорисовке (низкая прозрачность) 
3. Визуальный уровень HP, брони и статуса AFK (только если игрок в прорисовке)
- Отображение ХП на окружающем транспорте
- Отображение раскладки, капса и кол-ва символов под строкой чата
- Отображение текущих ежедневных заданий с описанием, таймером до следующего обновления заданий (зависит от выбранного часового пояса)
- Отображение наличия и количества, выбранных в меню, предметов из инвентаря игрока
- Отображение Cooldown до следующего ограбления дома и автоугона
![ ](https://i.imgur.com/nXCb89Y.png)	   
	   
## Биндер
- Добавить бинд
- Редактировать бинд
- Переместить бинд
- Задать клавишу или команду
- Использовать переменные
![ ](https://i.imgur.com/rpROkpj.png)

## Все команды скрипта
- /srp (/samprp) — открыть/закрыть главное меню скрипта
- /setov (/setoverlay) — изменить местоположения элементов оверлея на экране
- /srpflood [Text] (/samprpflood [Text]) — флудить заданным текстом в чат
- /srpstop — очистить очередь отправляемых сообщений в чат (очень полезно если биндер флудит без остановки)
- /srpup (/samprpup) — обновить скрипт
- /whenhouse — узнать когда слетит недвижимость
![ ](https://i.imgur.com/zqG6Cu2.png)