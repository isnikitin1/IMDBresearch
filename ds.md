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

1. title - Наименование фильма (категориальный, номинальный);
2. average_rating - Усредненный рейтинг IMDb (числовой, непрерывный);
3. director - Режиссер (категориальный, номинальный);
4. writer - Сценарист (категориальный, номинальный);
5. metascore - Оценки из <a href="https://www.metacritic.com/">Metacritic</a> (числовой, непрерывный);
6. cast - Ключевые актеры (категориальный, номинальный);
7. country_of_origin - Страна происхождения (категориальный, номинальный);
8. languages - Языки (категориальный, номинальный);
9. runtime - Длительность (числовой, дискретный);
10. genre - Жанр (категориальный, номинальный);
11. budget - Бюджет (числовой, дискретный);
12. worldwide_gross - Кассовые сборы (числовой, дискретный);
13. release_year - Дата выхода (числовой, дискретный);
14. profit_or_loss - Прибыль/убыток (числовой, дискретный);
15. p&l_rate - Отношение прибыли/убытка к бюджету фильма (числовой, непрерывный).

### Размер объединенного датасета содержит 1455 записей