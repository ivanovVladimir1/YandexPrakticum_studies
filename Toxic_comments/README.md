## Определение токсичных комментариев

Интернет-магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

необходимо классифицировать комментарии на позитивные и негативные. 

#### Используемые библиотеки
pandas numpy matplotlib scikit-learn lightgbm nltk pytorch re

## Общий вывод

Обучены модели классификации логистической регрессии, случайного леса LGBM.  
Оценка моделей проводилась по метрике F1-score.

С небольшим перевесом максимальный показатель метрики выдала модель логистической регрессии.

Лучшая модель проверена на тестовой выборке. Показатель целевой метрики составил 0,778, что удовлетворяет поставленной задаче.

---

Также проведен эксперимент с использованием нейронной сети BERT для поиска токсичных комментариев.  
Она показала заметно лучший результат (0,92).
