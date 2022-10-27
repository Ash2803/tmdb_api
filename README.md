# Что делает
Выводит пользователю до 8 схожих на его запрос фильмов, находит фильм в базе данных,
создает свою базу данных из фильмов и получает бюджет выбранного фильма.

# own_db_helpers.py
- Возвращает данные о фильмах в формате JSON;
- Импортируется в `find_similar.py` в переменную `films_data` 
и используется функциях `find_my_film` и `get_rating`;
- Импортируется в `search_in_db.py` , используется в переменной `films_data`.

# find_similar.py
- Ищет указанный пользователем фильм в указанной пользователем БД, 
если фильм найден, то возвращает пользователю до 8 похожих фильмов;
- Запустить скрипт:
```
python find_similar.py
```

# tmdb_helpers.py
- Выполняет запрос в БД, и получает ответ в JSON формате,
используется в `make_own_db.py` и `get_movie_budget`.

# search_in_db.py
- Поиск фильма в БД.
- Запустить скрипт:
```
python search_in_db.py
```

# make_own_db.py
- Создает список фильмов в формате JSON.
- Запустить скрипт:
```
python make_own_db.py
```

# get_movie_budget.py
- Выводит бюджет выбранного фильма;
- Запустить скрипт:
```
python get_movie_budget.py
```



