# Сайт для парикмахерской

**Стэк технологий backend:**
 - терминал Linux;
 - Python;
 - Django;
 - djangorestframework;
 - djoser;
 - Pillow;
 - gunicorn;
 - nginx;
 - python-dotenv

### Как запустить проект:

##### Клонировать репозиторий:

```
git clone git@github.com:LeoNefesch/salon_hair.git
```

##### Настройка backend-приложения проекта.

Перейти в директорию backend-приложения проекта.

```
cd salon_hair/backend/
```

Cоздать и активировать виртуальное окружение :

```
python3 -m venv venv
```

* Если у вас Linux/macOS

    ```
    source venv/bin/activate
    ```
    или
    ```
    . venv/bin/activate
    ```

* Если у вас windows

    ```
    source venv/scripts/activate
    ```

Обновить pip:

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```


Нахадясь в папке с файлом manage.py, выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

Остановить запущенное приложение и передать управление в терминал:

```
Ctrl + C
```