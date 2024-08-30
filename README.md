# Разработка модели, выявляющей токсичные комментарии

**Цель проекта**

Построение модели, способной классифицировать комментарии на позитивные и негативные со значением метрики качества *F1* не меньше 0.75. 

**Этапы работы**

1. Разведочный анализ.
2. Лемматизация, удаление стоп-слов.
3. Векторизация с помощью TF-IDF.
4. Построение модели. 
5. Выводы.

**Описание данных**

Данные находятся в файле `toxic_comments.csv`. Столбец *text* в нём содержит текст комментария, а *toxic* — целевой признак.
