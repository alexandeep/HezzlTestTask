## Задание 1.

### 01. Отоборжание надписи NoMoves
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Заполнить в конструкторе игровые поля так, чтобы игроку не оставалось ходов
Запустить игру и очистить поле с помощью бонусов так, чтобы игра дальше была возможна
#### Результат:
Надпись "No moves" продолжает отображаться в течение всей игры
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)

02. Сообщение о выигрыше после истечения времени
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Заполнить в конструкторе игровые поля
Запустить игру
Ждать окончания таймера
С помощью бонусов выполнить условия для выигрыша
#### Результат:
Сайт присылает уведомление о выигрыше
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)

03. Отображение времени на таймере
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Выбрать время таймера больше чем 3710 сек.
Запустить игру
Дождаться обнуления таймера
#### Результат:
В начале игры таймер отображает время 00:10
Через 10 секунд таймер после 00:00 показывает 59:59
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)

04. Конструктор не импортирует уровень
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Заполнить уровень
Перейти в меню сохранения
Нажать на кнопку "EXPORT" и сохранить JSON-файл
Нажать на кнопку "IMPORT" и выбрать раннее сохранённый JSON-файл
#### Результат:
Конструктор выдаёт ошибку в шапке сайта
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)

05. Зависание конструктора
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Заполнить уровень
Перейти в меню сохранения
Нажать на кнопку "Reset"
#### Результат:
Конструктор зависает и не реагирует на действия пользователя
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)


06. Некорректная работа функции "Spawner"
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Перейти во вкладку "settings" справа сверху
Перейти во вкладку "spawn (global)"
Изменить параметры спавна, оставив 1 объект
#### Результат:
Изменение объекта в меню не влияет на то какой объект спавнится
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)


07. Зависание игры
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Заполнить поля бустерами
Запустить игру и попробовать передвинуть бустеры
#### Результат:
Игра зависает и не реагирует на действия пользователя
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)


08. Съезжание вёрстки
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Выбрать элемент из списка справа и нажать на поле
#### Результат:
Меню в шапке сайта съезжает на несколько мс
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)


09. Бесконечная игра
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Оставить игровые поля пустыми
Запустить игру
Включить режим игры бота
#### Результат:
Нет возможности выполнения условий для победы
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)


10. Отображение полоски прогресса в шапке сайта
#### Предусловие:
Открыть сайт: https://g.hezzl.com/f10/match3/
Перейти во вкладку конструктора слева сверху
#### Шаги воспроизведения:
Создать новое игровое поле
Заполнить поле для кол-ва 1 фигуры во вкладке GOAL большим значением
Запустить игру
Подождать пару секунд
#### Результат::
Полоска #### Результат:а в шапке сайта обнуляется, хотя цель не была выполнена
#### Окружение:
Операционная система: Windows 10 Pro 22H2
Веб-браузер: Google Chrome Версия 126.0.6478.183, (64 бит)

## Задание 3.
SELECT *
FROM your_table_name
WHERE campaignId = 145602
  AND date >= '2023-12-31' 
  AND date < '2024-01-31';