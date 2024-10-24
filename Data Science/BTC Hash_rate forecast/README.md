# Проект модель прогнозирования хешрейта сети BTC

Данный проект направлен на применение методологии прогнозирования временных рядов в целях прогнозирования хешрейта сети BTC

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

По итогам применения модели был разработан прогноз на период до следующего халвинга*

Халвинг (от англ. “halving” — “половина”) — это запланированное событие в протоколе Биткойна, при котором награда за добычу блока уменьшается вдвое. Это событие происходит примерно каждые 210 000 блоков, что примерно соответствует каждые четыре года. Халвинг является одним из ключевых элементов денежно-кредитной политики Биткойна и играет важную роль в его экономике и устойчивости.

<img width="570" alt="image" src="https://github.com/user-attachments/assets/40c89a13-d60f-4cc3-aa3d-5b5c39f57004">

Учитывая, что текущая награда сети составляет 3.125 BTC каждые 10 минут, используя прогнозные данные можно применить для расчета теоретической награды майнинговой фермы. 
