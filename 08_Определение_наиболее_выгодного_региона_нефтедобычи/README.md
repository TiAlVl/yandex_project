# Определение наиболее выгодного региона нефтедобычи


## Данные

Для каждой скважины в трёх регионах имеются уже известные данные геологоразведки о характеристиках нефти.

## Задача

На основе данных геологоразведки необходимо выбрать район добычи нефти

необходима модель для определения региона, где добыча нефти принесёт наибольшую прибыль. 
Ориентироваться на метрику RMSE
Оценить вероятность убытка, допустимый предел менее 2,5%

## Используемые библиотеки
- Pandas
- Scikit-learn
- бутстреп

## Вывод

В ходе выполнения проекта:

- Был подготовлен датасет для обучения моделей
- для каждого региона обучили модель машинного обучения линейной регресии
- в ходе анализа полученных данных метрик RMSE, прогнозируемых прибыли и рисках , был выбран регион добычи нефти
