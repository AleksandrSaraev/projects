# Предсказание восстановления золота
## Статус:  
Завершен 
## Цель проекта:
На основе параметров каждой стадии (флотация, первичная очистка, вторичная очитска) очистки золота из золотосодержащей руды, создать модель машинного обучения предсказывающую коэффициент восстановления золота из золотосодержащей руды. В качестве метрики принять sMAPE.
## Сделано:
- Проверка и предобработка данных
- Исследовательский анализ данных
- Построение и сравнение нескольких моделей машинного обучения
- Подбор гиперпараметров и проверка итоговой модели на тестовой выборке
## Вывод:
- Рассмотрено 4 модели: LinearRegression, DecisionTreeRegressor, RandomForestRegressor, GradientBoostingRegressor
- Лучшие результаты показала модель GradientBoostingRegressor с результатом sMAPE 8.24%
- Выбранная модель проверена на адекватность, с помощью сравнения с константной моделью
## Библиотеки:
Pandas  
sklearn  
numpy  
Matplotlib 
