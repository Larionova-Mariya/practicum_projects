# Определение перспективного тарифа для телеком-компании
<b>Цель:</b> проанализировать поведение клиентов и определь лучший из двух тарифов.

<b>Входные данные:</b> информация о 500 пользователях оператора сотовой связи (возраст, город, тариф, длительность звонков, количество сообщений, объём интернет-трафика).

<b>Этапы работы:</b>
- предобработка данных
- анализ данных
- проверка гипотез
- выводы

<b>Предобработка данных:</b>
- привести данные к нужным типам,
- найти и исправить ошибки в данных,
- посчитать для каждого пользователя: количество сделанных звонков и израсходованных минут разговора по месяцам, количество отправленных сообщений по месяцам, объем израсходованного интернет-трафика по месяцам,
- посчитать помесячную выручку с каждого пользователя,

<b>Анализ данных:</b>
- определить, сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц, 
- посчитать среднее количество, дисперсию и стандартное отклонение,
- построить гистограммы,

<b>Проверка следующих гипотез:</b>
- средняя выручка пользователей тарифов «Ультра» и «Смарт» различаются,
- средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов,

<b>Выводы:</b>
- Суммарная средная продолжительность звонков пользователей тарифа ultra больше (около 600 мин), чем продолжительность звонков пользователей тарифа smart (около 400 мин). Суммарная продолжительность звонков пользвателей тарифа ultra сохранялась высокой в течении четырёх месяцев, пользователей тарифа smart - трёх месяцев.
- Ежемесячное количество звонков пользователей тарифа smart - около 60 в течении четырех месяцев, пользователей тарифа ultra - около 80 звонков в течении трёх месяцев. Пользователи тарифа ultra тратят больше mb интернета в месяц (20000), чем пользователи тарифа smart (16000).
- В течении 7 месяцев пользователи тарифа smart отправляли в среднем около 40 сообщений. У пользователей тарифа ultra среднее количество сообщений в месяц доходило до 70.
- Среднемесячная выручка с тарифа smart (523 345.35) больше, чем ultra (102 024.49).
- Cредняя выручка пользователей из Москвы не отличается от средней выручки пользователей из других регионов.
- Пользователи тарифа ultra совершают больше звонков, используют больше интернета, отправляют больше сообщений.
- В выборке больше пользователей тарифа smart (349), чем тарифа ultra (143). Процент переплачивающих пользователей тарифа smart - 95.1%, тарифа ultra - 11.7%.
- Для мобильного оператора тариф smart выгоднее, чем тариф ultra.