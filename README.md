# Yatube
(❁´◡`❁)
### Социальная сеть для блоггеров
Python 3.7
Django 2.2.19

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Gatitka/api_final_yatube.git
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

### URLS
"v1/posts": "http://127.0.0.1:8000/api/v1/posts/"
просмотр, создание, редакция постов

"'v1/comments/: "http://127.0.0.1:8000/api/v1/(<post_id>)/comments"
просмотр, создание, редакция комментов к постам

"v1/groups": "http://127.0.0.1:8000/api/v1/follow/",
просмотр групп

"v1/follow": "http://127.0.0.1:8000/api/v1/follow/"
просмотр, создание подписок


### Plugins

| Plugin | README |
| ------ | ------ |
| GitHub | [https://github.com/Gatitka/yatube_project/blob/main/README.md][PlGh] |


### Лицензия

BSD-3

**"Настоящих буйных мало, и те стали нынче блогерами"**

### Автор
Наталья Кириллова
✨Magic ✨

