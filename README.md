# data_science_ya
Yandex_Practicum

Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме  "Специалист по Data Science".

| Название проекта | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [1.Музыка больших городов](1.yandex_music) | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница)| Pandas |
| [2.Исследование надёжности заёмщиков — анализ банковских данных](2.credit) | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок|Pandas|
|[3.Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](3.real_estate) | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра|Pandas, Matplotlib|
|[4.Определение выгодного тарифа для телеком компании](4.tariff) | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. |Pandas, Matplotlib, NumPy, SciPy|
|[5.Изучение закономерностей, определяющих успешность игр](5.computer_games) | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний |NumPy, Pandas, Matplotlib|
|[6.Классификаиция клиентов телеком компании](6.telecom_client_classification) |Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям один из новых тариф|Python, Pandas, Matplotlib, Scikit-learn|
|[7.Прогнозирование оттока клиента Банка](7.bank_client_churn) |Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет|Pandas, Matplotlib, Scikit-learn|
|[8.Определение наиболее выгодного региона нефтедобычи](8.Oil_wells) |Предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль|Pandas, Matplotlib, Scikit-learn|
|[9.Исследование технологического процесса очистки золота](9.Gold_production) |Строитстся модель машинного обучения для промышленной компании, разрабатывающая решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.|Pandas, Matplotlib, Scikit-learn|
|[10.Защита данных клиентов страховой компании](10.Client_data_protections) |Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. |Pandas, Matplotlib, NumPy, Scikit-learn|
|[11.Построение модели определения стоимости автомобиля](11.car_price) |Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля| Pandas, CatBoost, LGBM|
|[12. Исследование базы данных сервиса Stackoverflow]() |Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания|SQL, SQLAlchemy, Python, NumPy, Pandas, Matplotlib,Seaborn|
|[13.Прогнозирование количества заказов такси на следующий час](13.taxi_orders) |В этом исследовании работа идёт с базой данных StackOverflow — сервиса вопросов и ответов о программировании. StackOverflow похож на социальную сеть — пользователи сервиса задают вопросы, отвечают на посты, оставляют комментарии и ставят оценки другим ответам|Python, NumPy, Pandas, Scikit-learn, statsmodels|
|[14.Обучение модели классификации комментариев](14.text_analysis) |СИнтернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию|Python, Pandas, BERT, nltk, tf-idf|
|[15.Обработка фотографий покупателя](15.Photo) |Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя.|Python, Keras|
|[16.Прогнозирование оттока телеком компании](telecom_churn) |Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах|Pandas, Matplotlib, NumPy, Scikit-learn|
