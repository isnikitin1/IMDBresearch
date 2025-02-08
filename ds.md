# Разведочный анализ данных IMDb

## Предполагается исследовать рейтинги, бюджет и доходы в эквиваленте usd

### В работе будет использован объединенный набор данных из открытых источников (ресурс kaggle)

<a href="https://www.kaggle.com/datasets/hetbabariya/imdb-movies-data-collection-5000-records">IMDb Movies Data
Collection (5000 Records)</a>

Описание данных датасета:

1. Title - Наименование фильма;
2. Average Rating - Усредненный рейтинг IMDb;
3. Director - Режиссер;
4. Writer - Сценарист;
5. Metascore - Оценки из <a href="https://www.metacritic.com/">Metacritic</a>;
6. Cast - Ключевые актеры;
7. Release Date - Дата выхода.
8. Country of Origin - Страна происхождения;
9. Languages - Используемые языки.
10. Budget - Бюджет;
11. Worldwide Gross - Кассовые сборы;
12. Runtime - Длительность.

<a href="https://www.kaggle.com/datasets/gayu14/tv-and-movie-metadata-with-genres-and-ratings-imbd">TV & Movie Metadata
with Genres and Ratings (2023) 130000 Records)</a>

Описание данных датасета:

1. movie - Наименование фильма;
2. genre - Жанр;
3. runtime - Длительность;
4. certificate - Возрастное ограничение;
5. rating - Усредненный рейтинг;
6. stars - Ключевые актеры;
7. description - Описание.
8. votes - Голоса или рейтинг среди оценщиков;
9. director - Режиссер.

### Объединенный датасет содержит следующие поля:

1. title - Наименование фильма;
2. average_rating - Усредненный рейтинг IMDb;
3. director - Режиссер;
4. writer - Сценарист;
5. metascore - Оценки из <a href="https://www.metacritic.com/">Metacritic</a>;
6. cast - Ключевые актеры;
7. country_of_origin - Страна происхождения;
8. languages - Языки.
9. runtime - Длительность;
10. genre - Жанр;
11. budget - Бюджет;
12. worldwide_gross - Кассовые сборы;
13. release_year - Дата выхода.
14. profit_or_loss - Прибыль/убыток;
15. p&l_rate - Отношение прибыли/убытка к бюджету фильма.

### Размер объединенного датасета содержит 3543 записи