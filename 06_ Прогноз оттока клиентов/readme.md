# Прогноз оттока клиентов
## Статус:  
Завершен 
## Цель проекта:
Имеются данные о клиентах банка (возраст, пол, кредитный рейтинг, баланс на счете, наличие кредитной карты, активность клиента и т.п). Необходимо создать модель машинного обучения, предсказывающую уйдет клиент в билижайшее время из банка или нет. Метрика F1-мера (должна быть больше 0,59), ROC-AUC.
## Сделано:
- Проверка и предобработка данных
- Исследовательский анализ данных
- Построение и сравнение нескольких моделей машинного обучения
- Подбор гиперпараметров и проверка итоговой модели на тестовой выборке
## Вывод:
- Выполнено сравнение нескольких вариантов с дисбалансом классов
- Рассмотрено 3 модели: логическая регрессия, решающее дерево, случайный лес
- Лучшие результаты показала модель сдучайного леса
- С помощью выбранной модели достигнута метрика F1-мера не меньше 0.59 - 0.62
- Выбранная модель проверена на адекватность, с помощью сравнения со случайной моделью
## Библиотеки:
Pandas  
sklearn  
numpy  
Matplotlib 
