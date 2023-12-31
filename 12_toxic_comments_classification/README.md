# Классификация комментариев по их токсичности

**Статус проекта:** Завершен

**Используемые библиотеки**
* textwrap
* re
* pandas
* numpy
* matplotlib
* sklearn
* spacy
* tqdm
* nltk 
* wordcloud
* lightgbm
* catboost

**Описание проекта**\
Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.\
Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.\
Постройте модель со значением метрики качества F1 не меньше 0.75.

**Цель**\
Построить модель, предсказывающую токсичность комментария

**Вывод**\
По результатам исследования, в качестве лучшей модели выла выбрана модель логистической регрессии, показавшая F1=0.7566.

**Описание данных**\
Данные находятся в файле /datasets/toxic_comments.csv.\ 
Столбец text в нём содержит текст комментария, а toxic — целевой признак.