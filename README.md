# Deeplearning
Project by Deeplearning class Dimas

Что нужно:
1. Склеить все метрики и получить единый датафрейм для всех данных(историчные)
2. Очистить датафрейм от нулов, строковых значений, ненужных метрик(timestamp)
3. Построить модель KMNEAS с оптимальным количеством кластером(метод локтя)
4. Установить Git, Создать репозиторий
и делать комиты и ПРы 

Что сделала Аделя:
1) подготовила данные для кластеризации
В Спарк требуется определенным образом переформированный дата фрейм для кластеризации
2) реализовала функцию поиска оптимального числа кластеров методом локтя
3) реализовала кластеризации по заданному числу k, ее используем после того как нашли 
это оптимальное k и вывожу центры кластеров
