### Учкебный проект на тему:
### Разработка модели, выявляющей токсичные комментарии

---

#### [Исходный код проекта](https://github.com/nightcarpenter/ToxicComments/blob/main/toxic_comments.ipynb)

---

#### Цель проекта

Построение модели, способной классифицировать комментарии на позитивные и негативные со значением метрики качества *F1* не меньше 0.75. 

---

#### Этапы работы

1. Разведочный анализ.
2. Лемматизация, удаление стоп-слов.
3. Векторизация с помощью TF-IDF.
4. Построение модели.

---

#### Описание данных
- *text* — текст комментария
- *toxic* — целевой признак

---

#### Вывод

Была разработана модель, определяющая токсичность комментариев.

Метрика F1 на тестовой выборке равна 0.77, что удовлетворяет требованию заказчика (минималоьный порог 0.75).

Процесс лемматизации может занимать достаточно продолжительное время (около получаса на тренировочной выборке).
