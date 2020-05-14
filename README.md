# Data-Analysis-projects-Yandex.Practicum
Jypiter notebooks

Описание выполненных проектов курса [Data Analyst Yandex.Praktikum:](https://praktikum.yandex.ru/data-analyst)
---

1.  ### [Анализ товарного ассортимента интернет-магазина](https://nbviewer.jupyter.org/github/AnnaShevalje/Data-Analysis-projects-Yandex.Prakticum-cohort-5/blob/02c19d85a26221ed2111a4b2ecedf5ab0e9f7d15/ECommerce_assortment_analysis.ipynb)
**Заказчик** - интернет-магазина товаров для дома и быта "Пока все ещё тут". 

**Задача:**  Проанализировать товарный ассортимент. Сегментировать товарный ассортимента на основной и дополнительный. Выработать рекомендации на предмет: какой ассортимент следует закупать магазину в первую очередь, какой во вторую, а на какой вообще не стоит тратиться. Проверить статистические гипотезы. 

**Использовались следующие навыки:**  предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), визуализация Plotly, Seaborn. Проверка гипотез Т критерием (о равенстве средних выборок), применение методов ML (кластеризация с использованием библиотеки sklearn.cluster Kmeans, построение дендрограммы).

**Что сделано:** ассортимент сегментирован на основной и дополнительный, провены статистические гипотезы, ассортимент кластеризирован с применением методов ML,  разработаны рекомендации на предмет: какой ассортимент следует закупать магазину в первую очередь, какой во вторую, а на какой вообще не стоит тратиться.


2.  ### [Анализ оттока клиентов и разработка плана действий по их удержанию](https://nbviewer.jupyter.org/github/AnnaShevalje/Data-Analysis-projects-Yandex.Prakticum-cohort-5/blob/ff92b62caf4bbdda9621cf0f3f8450e8e99ed4fc/Churn_prediction_ML.ipynb)
**Заказчик** – сеть фитнес клубов. 

**Задача:** провести анализ и подготовить план действий по удержанию клиентов.

**Использовались следующие навыки:** предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), визуализация Plotly, Seaborn. применение методов ML (кластеризация, , построение дендрограммы, обучение модели прогнозирования оттока клиентов с использованием логистической регрессии, случайного леса, оценка показателей accuracy, precision и recall). Использовальсь библиотеки sklearn.cluster, sklearn.linear, sklearn.tree, sklearn.ensemble, sklearn.metrics, scipy.cluster.hierarchy, sklearn.preprocessing, sklearn.linear_model, sklearn.model_selection и прочие.

**Что сделано:** Сформулированы основные выводы и предложены рекомендации для стратегии взаимодействия с пользователями и их удержания. Описаны типичные кластеры клиентов, даны рекомендации по работе с наиболее преспрективными из них.

3. ### [Оптимизация маркетинговых затрат по каналам инвестирования](https://nbviewer.jupyter.org/github/AnnaShevalje/Data-Analysis-projects-Yandex.Prakticum-cohort-5/blob/be4a30b59ec209f883cc3cdcbb10f9f2d8c99df3/Business_rates_analysis.ipynb)

**Заказчик** – Онлайн.Афиша - сервис поиска и покупки билетов на мероприятия. 

**Задача:** оптимизация маркетинговых затрат по каналам инвестирования.

**Использовались следующие навыки:** предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), расчет бизнес метрик (расчет LTV, CAC, RetentionRate, Churn rate, ROMI, DAU/MAU, когортный анализ, построение heatmap, построение гистрограмм, «ящиков с усами».

**Что сделано:** проанализированы затраты и окупаемость инвестиций по различным каналам и типам источников, даны рекомендации отделу маркетинга по приоритизации инвестиций.

4. ### [SQL анализ рекламных инвестиций](https://nbviewer.jupyter.org/github/AnnaShevalje/Data-Analysis-projects-Yandex.Prakticum-cohort-5/blob/master/SQL_market_investment_analysis.ipynb)

**Заказчик** - онлайн-маркетплейсе «Заберу», онлайн магазин сувениров ручной работы от небольших производителей. 

**Задача:** Анализ эффективности рекламных акций компании.

**Использовались следующие навыки:** Подключения запросов через psycopg2-binary, коннекция к базе, использование библиотеки pandas, SQL запросы для получения нужных данных (использование аггрегирующих оператовров, конструкцуии WITH, команд group by, order by, join и т.д.

**Что сделано:** Проанализирована эффективность рекламных компании. Сделаны выводы.

5. ### [Анализ результатов АВ тестрования интернет магазина](https://nbviewer.jupyter.org/github/AnnaShevalje/Data-Analysis-projects-Yandex.Prakticum-cohort-5/blob/9c82466e39e5f1b8cbf417de9e1f07368a593dd4/AB_test_analysis.ipynb)

**Заказчик** - интернет-магазин. 

**Задача:** Оценка результов А/В теста (выявление изменений в воронке продаж), написание выводов.

**Использовались следующие навыки:** предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), расчета процентилей выборок, построения гистограмм визуализация Plotly, расчет и отрисовка продуктовой воронки, проверка гипотез Z критерием.(о равенстве долей) – АА и АВ тесты. 

**Что сделано:** построена воронка продаж клиентов магазина, проверены гипотезы об изменении воронки на основании результатов АВ тестирования.

6. ### [Анализ тарифов оператора сотовой связи](https://nbviewer.jupyter.org/github/AnnaShevalje/Data-Analysis-projects-Yandex.Praktikum/blob/master/mobile_operator_tariff_analysis.ipynb)

**Заказчик** – оператор сотовой связи.

**Задача:** Анализ тарифов федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

**Использовались следующие навыки:** предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), построение гистрограмм, проверка гипотез о равенстве средних в выборках 

**Что сделано:** проанализированы затраты по тарифам, рассчитаны дисперсия, стандартное отклонение, средняя выручка, длительность сессий, проверены гипотезы о равенстве средних в выручках по тарифам.

7. ### [Приоритизация гипотез и анализ результатов А/В теста для интернет-магазина](https://nbviewer.jupyter.org/github/AnnaShevalje/Data-Analysis-projects-Yandex.Prakticum-cohort-5/blob/master/hypothesis_priority_ABtest.ipynb) 

**Заказчик** - крупный интернет-магазин.

**Задача:** Приоритизация гипотез для крупного интернет-магазина. Запуск  A/B-теста и анализ его результатов

**Использовались следующие навыки:**  фреймворки  ICE\RICE, выявление наличия статистической значимости при проведении АВ теста, расчет процентилей выборок. 

**Что сделано:** приоритизированы гипотезы, проведен и проанализирован АВ тест, принато решение по результатам (тест остановлен, статистическая значимость в различии выборок достигнута).

8. ### [Анализ рынка заведений общественного питания г.Москва](https://nbviewer.jupyter.org/github/AnnaShevalje/Data-Analysis-projects-Yandex.Praktikum/blob/595ec5b171b4844dfd875d040d14600ce08259cc/Moscow_public_catering_analysis.ipynb)

**Заказчик** - предприниматели, планирующие открыть кафе в г.Москва

**Задача:** Анализ рынка заведений общественного питания города Москва для определения перспективного направления для открытия нового кафе.

**Использовались следующие навыки:**  предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), расчета процентилей выборок, построения графиков плотности распределения, гистограмм визуализация Plotly, оформление презентации в РРТ.

**Что сделано:** проанализированы заведения общепита по сетевому признаку, количеству посадочных мест, району города, количеству заведений на улице, даны рекомендации, оформлена презентация РРТ.

9. ### [Анализ результатов АВ тестрования стартапа по продаже продуктов питания](https://nbviewer.jupyter.org/github/AnnaShevalje/Data-Analysis-projects-Yandex.Prakticum-cohort-5/blob/133310f7c0ddc02055ce5409ed2e68cda2105c33/AB_test_analysis_food_startup.ipynb)

**Заказчик** – стартап по продаже продуктов питания. 

**Задача:**  анализ поведения пользователей мобильного приложения (анализ воронки продаж). Исследование результатов АВ теста – о наличии изменений в воронке продаж после изменения шрифта в приложении.

**Использовались следующие навыки:**  предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), расчета процентилей выборок, построения гистограмм визуализация Plotly, расчет и отрисовка продуктовой воронки, проверка гипотез Z критерием.(о равенстве долей) – АА и АВ тесты.

**Что сделано:** построена воронка продаж клиентов магазина, проверены гипотезы об изменении воронки на основании результатов АВ тестирования.

10. ### Создание автоматизированного дашборда Онлайн.Дзен

Заказчик – Онлайн.Дзен. Задача – построение автоматизированого обновляемого дашборда для отслеживания взаимодействий пользователей с карточками  Онлайн.Дзен с разбивкой по темам и понимания насколько хорошо пользователи конвертируются из показов карточек в просмотры статей.
Использовались следующие навыки: написание скрипта пайплайна (запись из сырых данных базы в агрегирующие таблицы), кода дашборда (библиотека dash), презентации в РРТ
Что сделано: написан скрипт пайплайна, дашборда, инструкция к тому, как запустить все файлы из виртуальной машины (readme.txt), файл с необходимыми библиотеками (requirements.txt)

11. ### Анализ клиентов кредитного отдела банка
Заказчик – кредитный отдел комменрческого банка. Задача: Анализ клиентов кредитного отдела банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.
Использовались следующие навыки: предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), лемматизация, категоризация данных
Что сделано: проанализированы доли должников в зависимости от доходов и наличия детей, лемматизированы основные цели кредитования, заемщики категоризированы по типу занятости.

12. ### Исследование сервиса Онлайн.Недвижимость

Заказчик - Яндекс.Недвижимость. Задача: Исследование сервиса Онлайн.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.
Использовались следующие навыки: предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), построение гистрограмм, «ящиков с усами», матрицы рассеяния, матрицы корреляций,  описание зависимостей на основе графиков.
Что сделано: проанализирован рынок (локации, стоимость, цена за кВ.метр, зависимости удаленности от центра города, определена граница центра по скачку стоимости кв.метра, проанализированы выбросы цен и корреляции между различными характеристиками объявлений).

13. ### Анализ рынка компьютерных игр

Заказчик – интернет магазин компьютерных игр. Задача: Анализ рынка для интернет-магазина который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Требовалось выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
Использовались следующие навыки: предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), построение гистрограмм, проверка гипотез о равенстве средних в выборках, построение гистрограмм, «ящиков с усами», матрицы рассеяния, матрицы корреляций, описание зависимостей на основе графиков (Plotly, Mathplotlib, Seaborn).
Что сделано: проанализированы продажи, рейтинги, популярность и активность выхода игр по платформам, даны рекомендации о наиболее перспективной платформе для запуска игр на будущий период.

14. ### Анализ спроса на пассажирские авиарейсы

Заказчик - российская авиакомпания. Задача: Анализ спроса пассажиров на рейсы в города, где проходят крупнейшие фестивали. Выявление зависимостей.
Использовались следующие навыки: парсинг данных, HTML, BeautifulSoup,  get-запросы, SQL, описание зависимостей на основе графиков (Plotly, Mathplotlib, Seaborn).
Что сделано: данные были спарсены из веб ресурса, приведены к формату датафрема и проанализированы, визуализированы, проверены гипотезы о наличии зависимостей.



