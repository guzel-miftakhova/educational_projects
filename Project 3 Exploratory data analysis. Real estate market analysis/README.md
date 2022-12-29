## Исследование объявлений о продажe квартир  в Санкт-Петербурге - анализ рынка недвижимости

**Статус проекта:**   *завершен*

**Использованные библиотеки:** `pandas`, `matplotlib`

### Описание проекта:

В нашем распоряжении данные сервиса Яндекc.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые получены автоматически на основе картографических данных. 
Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. 

**Наша задача**
    
  Установить параметры для определения рыночной стоимости объектов недвижимости. Это позволит построить автоматизированную систему:
  она отследит аномалии и мошенническую деятельность. 

**Ход исследования**

Исследование пройдёт в три этапа:
 1. Обзор данных.
 2. Предобработка данных.
 3. Установление параметров.
 
 **Выводы по проекту:**
 
 На стоимость объекта недвижимости, как в Санкт-Петербурге так и в соседних населённых пунктах, значительно влияет:
 - его площадь, количество комнат, есть обратная зависимость с удаленностью от центра;
 - в центральном районе Санкт-Петербурга больше предпочитают последние этажи, чем первые, однако не зависимо от района большинство представленных квартир расположены на промежуточных этажах;
 - а их стоимость примерно в 2 раза ниже, чем у квартир первых и последних этажей.