# Прогнозирование коэффициентов восстановления золота из золотосодержащей руды

## Описание проекта

Необходимо построить модель машинного обучения для промышленной компании, разрабатывающая решения для эффективной работы промышленных предприятий. 

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. 

Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

## Решение

Проведена проверка корректности расчета эффективности обогращения. Рассмотрено изменение концентрации металлов на различных этапах очистки сырья. Исследована суммарная концентрация всех веществ на разных стадиях. Составлена функция для расчета итогового показателя качества модели - метрики sMAPE (симметричное среднее абсолютное процентное отклонение). Обучено несколько моделей LinearRegression, Lasso, ExtraTreesRegressor, RandomForestRegressor, DecisionTreeRegressor, CatBoostRegressor.

## Результат

Лучший результат контрольной метрики sMAPE показала модель RandomForestClassifier - 2.95
