## Определение токсичных комментариев

Компания собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.

Значение метрики *RMSE* на тестовой выборке должно быть не больше 48.

#### Используемые библиотеки
pandas numpy matplotlib scikit-learn lightgbm catboost

## Общий вывод

Датасет ресемплирован до 1 часа. Данные выстроены в хронологическом порядке.

По исследованию датасета выявлено:
* Данные представлены за период с марта по август 2018 года, т.е. за ~5 месяцев;
* По трендам видно увеличение пользования сервисом на всем промежутке данных;
* Сезонность имеет суточный характер - днем больше заказов, ночью меньше. Также обнаружены всплески около часов пик.

Для каждой из них подобраны оптимальные гиперпараметры.

В целом все модели проходят необходимы порог по метрике (не более 48).

С результатом RMSE = 35.84 лучшей оказалась моделй CatBoost.
