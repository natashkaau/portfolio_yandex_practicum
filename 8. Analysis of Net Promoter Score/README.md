<a name="lists"><h1>Исследование опроса клиентов телекомунникацонной компании</h1></a>
[ipynb](https://github.com/natashkaau/portfolio/tree/main/8.%20Analysis%20of%20Net%20Promoter%20Score/NPS_project.ipynb)  
[Дашборд](https://public.tableau.com/app/profile/natashkaa.d/viz/MyViz2_16679881823630/Dashboard1?publish=yes)  
[Презентация](https://github.com/natashkaau/portfolio_yandex_practicum/blob/main/8.%20Analysis%20of%20Net%20Promoter%20Score/Presentation.pdf)  
<a name="lists"><h2>Данные</h2></a>

Таблица user:  
•user_id -	Идентификатор клиента, первичный ключ таблицы  
•lt_day - Количество дней «жизни» клиента  
•age -	Возраст клиента в годах  
•gender_segment - Пол клиента (1 – женщина, 0 – мужчина)  
•os_name - Тип операционной системы  
•cpe_type_name -	Тип устройства  
•location_id -	Идентификатор домашнего региона клиента, внешний ключ, отсылающий к таблице location  
•age_gr_id -	Идентификатор возрастного сегмента клиента, внешний ключ, отсылающий к таблице age_segment  
•tr_gr_id -	Идентификатор сегмента клиента по объёму потребляемого трафика в месяц, внешний ключ, отсылающий к таблице traffic_segment  
•lt_gr_id -	Идентификатор сегмента клиента по количеству месяцев «жизни», внешний ключ, отсылающий к таблице lifetime_segment  
•nps_score -	Оценка клиента в NPS-опросе (от 1 до 10)  

Таблица location:  
•location_id -	Идентификатор записи, первичный ключ  
•country -	Страна  
•city - Город  

Таблица age_segment:  
•age_gr_id -	Идентификатор сегмента, первичный ключ  
•bucket_min - Минимальная граница сегмента  
•bucket_max - Максимальная граница сегмента  
•title -	Название сегмента  

Таблица traffic_segment:  
•tr_gr_id - Идентификатор сегмента, первичный ключ  
•bucket_min - Минимальная граница сегмента  
•bucket_max - Максимальная граница сегмента  
•title -	Название сегмента  

Таблица lifetime_segment:  
•lt_gr_id - Идентификатор сегмента, первичный ключ  
•bucket_min - Минимальная граница сегмента  
•bucket_max - Максимальная граница сегмента  
•title -	Название сегмента  
<a name="lists"><h2>Задача</h2></a>
Определить текущий уровень потребительской лояльности, или NPS (от англ. Net Promoter Score), среди клиентов из России. 
<a name="lists"><h2>Навыки и инструменты</h2></a>
•SQL  
•Python  
•Pandas  
•Tableau  
•Построение дашбордов  
<a name="lists"><h2>Общий вывод</h2></a>
Определен текущий уровень потребительской лояльности, или NPS (от англ. Net Promoter Score), среди клиентов из России. Создан дашборд в Tableau, создана презентация.
