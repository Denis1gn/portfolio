# Проект модель прогнозирования хешрейта сети Биткойн

Данный проект направлен на применение методологии прогнозирования временных рядов в целях прогнозирования хешрейта сети Биткойн

Источник данных: https://www.blockchain.com/ru/explorer/charts/hash-rate

__Хешрейт (или хэшрейт) сети Биткойн__ — это мера общей вычислительной мощности, которую все майнеры сети используют для обработки транзакций и обеспечения безопасности блокчейна. Проще говоря, хешрейт показывает, сколько хешей (криптографических вычислений) сеть способна выполнить в секунду. Для майнеров хешрейт напрямую связан с их потенциальной доходностью. Более высокий хешрейт требует больше энергии и оборудования, но также может привести к большей вероятности нахождения блока и получения награды. 

Данная модель была подготовлена с целью разработки прогноза хешрейта для финансовой модели инвестиционного проекта.

В ходе выбора модели проверялось качество прогноза следующих моделей:
- Линейная регрессия
- Catboost
- LightGBM
- XGBoost

По итогу лучшая модель - Catboost, RMSE на тестовых данных: 289,525,04.75

<img width="592" alt="image" src="https://github.com/user-attachments/assets/ad851464-6c27-4295-9130-87b238c7f073">

