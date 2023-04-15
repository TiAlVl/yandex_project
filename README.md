# Репозиторий для профессий "Аналитик данных" и "Специалист по Data Science"

## описание проектов 

Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных" / "Специалист по Data Science".

| Название проекта | Сфера деятельности | Описание | Используемые библиотеки | Ключевые<br>слова |
| :------------ | :-------------- | :---------------------- | :------------ | :------------ |
| [Музыка больших городов](01_Музыка_больших_городов) | - Интернет-сервисы <br> - Стриминговый сервис| Сравнение предпочтений  пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница)| *Python, Pandas* | обработка данных, дубликаты, пропуски, логическая индексация, группировка, сортировка |  
| [Исследование надёжности заёмщиков — анализ банковских данных](02_Исследование_надёжности_заёмщиков) | Банковская сфера, Кредитование | На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три.| *предобработка данных, Python, Pandas* |обработка данных, дубликаты, пропуски, категоризация, декомпозиция|
| [Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](03_Продажа_квартир_Санкт-Петербург) |Интернет-сервисы <br> Площадки объявлений| На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания.| *Python <br>Pandas <br> Matplotlib <br> исследовательский анализ данных <br> визуализация данных <br> предобработка данных* |обработка данных, histogram, boxplot, scattermatrix, категоризация, scatterplot,  фрод-мониторинг | 
| [Определение выгодного тарифа для телеком компании](04_Определение_выгодного_тарифа_для_телеком_компании) |Телеком | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов.| *Python <br> Pandas <br> Matplotlib <br> NumPy <br>SciPy <br>описательная статистика <br>проверка статистических гипотез* | обработка данных, histogram, boxplot, статистический тест, критерий Стьюдента|
| [Обработка фотографий покупателя](05_Обработка_фотографий_покупателя) | Бизнес <br> Оффлайн| Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Строится модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста.| *Python <br> Keras* |
| [Классификация клиентов телеком компании](06_Классификаиция_клиентов_телеком_компании) |Телеком| Сравнение предпочтений  пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница)| *Python <br> Pandas <br>Matplotlib <br>Scikit-learn* |
| [Прогнозирование оттока клиента Банка](07_Прогнозирование_оттока_клиента_Банка) | Бизнес <br> Инвестиции <br>Банковская сфера <br> Кредитование | Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.| *Pandas <br> Matplotlib <br> Scikit-learn* |
| [Определение наиболее выгодного региона нефтедобычи](08_Определение_наиболее_выгодного_региона_нефтедобычи) |Добывающие компании | предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль.| *Pandas <br>Scikit-learn <br> бутстреп* | регрессия, разработка бизнес-модели, бутстреп|
| [Исследование технологического процесса очистки золота](09_Исследование_технологического_процесса_очистки_золота) |Промышленность | Строитстся модель машинного обучения для промышленной компании, разрабатывающая решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.|*Python <br> Pandas <br> Matplotlib <br> NumPy <br> Scikit-learn <br> исследовательский анализ данных* | анализ данных, регрессия, кастомные метрики|
| [Защита данных клиентов страховой компании](10_Защита_данных_клиентов_страховой_компании) | Банковская сфера <br> Интернет-сервисы <br> Инвестиции <br> Телеком | Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. | *Python <br> NumPy <br> Scikit-learn* | линейная алгебра, регрессия| 
| [Построение модели определения стоимости автомобиля](11_Построение_модели_определения_стоимости_автомобиля) |Интернет-сервисы <br> Интернет-магазины <br> Бизнес | Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.| *Python <br> Pandas <br> lightgbm* | градиентный бустинг, регрессия|
| [Прогнозирование количества заказов такси на следующий час](12_Прогнозирование_количества_заказов_такси_на_следующий_час) | Бизнес <br> Интернет-сервисы <br> Стартапы |  Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания.| *Pandas <br> Scikit-learn <br>statsmodels* |
| [Обучение модели классификации комментариев](13_Обучение_модели_классификации_комментариев) |Интернет-сервисы <br> Стартапы | Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.| *Python <br> Pandas <br> BERT <br> nltk <br> tf-idf* | обработка естественного языка, NLP|
| [Анализ игрофых платформ](14_Анализ_игрофых_платформ) | Бизнес <br> Интернет-сервисы <br> Стартапы | Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.| *Python <br> Pandas <br> Matplotlib <br> NumPy <br>SciPy <br>описательная статистика <br>проверка статистических гипотез*|обработка данных, histogram, boxplot, статистический тест|
| [Прогнозирование оттока клиентов оператора связи](15_Прогнозирование_оттока_клиентов_оператора_связи) |Телеком  | Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.| *Python <br> Pandas <br> phik <br> Scikit-learn <br> catboost* |классификация, подбор гиперпараметров, выбор модели МО|


