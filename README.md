**Привет! Меня зовут Ирина, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.**


## Навыки и технологии

 - **Инструменты анализа данных:**
 
      <img src="https://cdn.icon-icons.com/icons2/627/PNG/512/sql-file-rounded-rectangular-outlined-interface-symbol_icon-icons.com_57503.png" width="40" />      <img src="https://cdn.icon-icons.com/icons2/1156/PNG/96/1486565571-microsoft-office-excel_81549.png" width="40" />

 - **Системы управления базами данных:**
      
      <img src="https://cdn.icon-icons.com/icons2/2415/PNG/96/mysql_original_wordmark_logo_icon_146417.png" width="45" /> <img src="https://cdn.icon-icons.com/icons2/2415/PNG/96/postgresql_original_wordmark_logo_icon_146392.png" width="45" />

 - **Средства визуализации данных:**
 
      <img src="https://cdn.icon-icons.com/icons2/2699/PNG/512/microsoft_powerbi_logo_icon_169958.png" width="100" />


## Проекты  


### Проект 1: Калькулятор юнит-экономики онлайн-школы <img src="https://cdn.icon-icons.com/icons2/1156/PNG/96/1486565571-microsoft-office-excel_81549.png" width="40" />

**Что нужно было сделать:** Построить юнит-калькулятор онлайн-школы

**Задача №1.** Рассчитать затраты на привлечение 1 юнита

**Задача №2.** Выяснить какой из каналов привлечения самый эффективный

**Задача №3.** Рассчитать все категории затрат и составить структуру юнит-экономики помесячно и сводную

**Задача №4.** Рассчитать, как сильно мы можем увеличить ФОТ, при этом сохранив заданный уровень маржинальности

**Задача №5.** Рассчитать новую маржинальность при изменении количества бесплатных уроков

**Задача №6.** Рассчитать, как изменятся маржинальность и LTR при изменении Retention

**Как решала:** Определила, что является юнитом дня нашей онлайн-школы, посчитала все виды затрат на один юнит, составила структуру юнит-эконимики и построила калькулятор, при изменении параметров которого, видно, как меняется маржинальность.

[**Ссылка на проект 1**](https://github.com/Irina-Rogozina/Data-analyst/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%821.xlsx)

**Выводы:** С помощью калькулятора легко и удобно можно отслеживать изменение маржинальности при корректировке некоторых параметров, таких как Retention, цена урока, ставки зарплаты учителей.  

  
  
### Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра <img src="https://cdn.icon-icons.com/icons2/1156/PNG/96/1486565571-microsoft-office-excel_81549.png" width="40" />

**Что нужно было сделать:** Понять насколько эффективна модель ежемесячной подписки в онлайн-кинотеатре.

**Задача №1.** Исследовать аудиторию онлайн-кинотеатра и рассчитать метрики для дальнейшего анализа динамики и эффективности

**Задача №2.** Создать юнит-калькулятор и предложить сценарий выхода на заданную маржинальность

**Задача №3.** Сделать наглядные визуализации по нашим пользователям - кто, где и что смотрит на нашей онлайн-платформе

**Как решала:** Рассчитала основные показатели по просмотрам, уникальным пользователям, первым просмотрам, Retention  и т.д., а также их динамику. Построила калькулятор юнит-экономики, зафиксировав ситуацию AS-IS и предложила сценарий для выхода на маржинальность 25%. Для наглядности построила визуализацию основных показателей.

[**Ссылка на проект 2**](https://github.com/Irina-Rogozina/Data-analyst/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%822.xlsx)

**Итог №1.** Сценарий выхода на более высокую маржинальность реален и осуществим.

**Итог №2.** Ежемесячная подписка - не самая эффективная модель для данного онлайн-кинотеатра.



### Проект 3: Анализ данных онлайн-школы <img src="https://cdn.icon-icons.com/icons2/627/PNG/512/sql-file-rounded-rectangular-outlined-interface-symbol_icon-icons.com_57503.png" width="40" />

**Задача №1.** Составить таблицу с id покупки и ее ценой в рублях по максимальному курсу на эту дату

**Задача №2.** Составить таблицу антитоп учителей, у которых ученики пропускают больше всего недель между занятиями.

**Как решала:** Создала подзапрос, который выбирает максимальную ставку для каждой валюты на каждую дату. Затем перемножила цену в валюте на ставку, указав, что, если валюта рубли, то оставляем цену как есть. Для каждой недели, в которой был урок, нашла следующую неделю, в которой был урок для каждого ученика. Посчитала разницу между данными неделями и определила сколько было пропущено недель. Для каждого учителя посчитала количество таких пропущенных недель и составила антирейтинг.

[**Ссылка на проект 3**](https://github.com/Irina-Rogozina/Data-analyst/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%823)


### Проект 4: Построение дашборда по прибыли для руководителя <img src="https://cdn.icon-icons.com/icons2/2699/PNG/512/microsoft_powerbi_logo_icon_169958.png" width="100" />

**Задача №1.** Показать прибыльность по каналам продаж

**Задача №2.** Показать динамику отгрузки товаров стоимостью выше 50 000

**Задача №3.** Показать какие бренды генерируют наибольшую выручку по "дорогим" товарам

**Задача №4.** Показать выручку отдельно по каждому бренду

**Задача №5.** Построить антитоп менеджеров по выручке от продаж и вывести названия брендов, по которым у каждого менеджера наименьшие продажи

**Задача №6.** Вывести самый прибыльный день в каждом месяце

**Как решала:** С помощью мер и вычисляемых столбцов посчитала общую выручку, долю каждого бренда в ней, выручку от продаж по каждому менеджеру и присвоила каждому менеджеру место в антирейтинге, посчитала прибыль от продаж "дорогих" товаров и вывела бренды, которые делают наибольшую выручку. А также построила график отгрузки "дорогих товаров" за весь период. И все это оформила на дашборде.

[**Ссылка на проект 4**](https://github.com/Irina-Rogozina/Data-analyst/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%824.pbix)

**Выводы:** В итоге получился двухстраничный дашборд, на котором руководитель может видеть данные и фильтровать их, как ему удобно, - по бренду, по каналу продаж, по менеджеру, а также отследить прибыль и динамику отгрузок "дорогих" товаров.

### Проект 5: Моделирование изменения балансов студентов <img src="https://cdn.icon-icons.com/icons2/627/PNG/512/sql-file-rounded-rectangular-outlined-interface-symbol_icon-icons.com_57503.png" width="40" />

**Что нужно было сделать:** Смоделировать изменение количества уроков на балансе студентов за каждый день заданного периода.

**Задача №1.** Создать таблицу, где будут начисления и списания уроков для каждого студента за каждый день периода

**Задача №2.** Смоделировать общий баланс всех уроков студентов

**Как решала:** Собрала таблицу всех дней заданного периода, таблицу со списком всех успешных покупок каждого студента за каждый день, то же самое со списком всех пройденных (списанных с баланса) уроков каждого студента за каждый день и собрала итоговый баланс по каждому студенту. Также создала таблицу с кумулятивным начислением и списанием уроков с баланса всех студентов и сделала визуализацию итогового результата.

[**Ссылка на проект 5**](https://github.com/Irina-Rogozina/Data-analyst/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%825.xlsx)

**Выводы:** Общий баланс стабильно рос в течение всего периода - это хорошо видно на графике. Покупки уроков растут быстрее, чем списания. Наибольший рост наблюдается с октября и до конца периода.

### Контактная информация

**E-mail:** irc.87@bk.ru

**Telegram:** @RogozinaIrina

