# Django testing

## Технологии:

- Python 3.9
- Django 3.2
- SQLite3
- Pytest
- Unittest

## Установка (Windows):

1. Клонирование репозитория

```
git clone https://github.com/StsdevkzCode/django_testing.git
```

2. Переход в директорию django_testing

```
cd django_testing
```

3. Создание виртуального окружения

```
python -m venv venv
```

4. Активация виртуального окружения

```
source venv/Scripts/activate
```

5. Обновите pip

```
python -m pip install --upgrade pip
```

6. Установка зависимостей

```
pip install -r requirements.txt
```

7. Переход в директорию ya_news

```
cd ya_news
```

8. Применение миграций

```
python manage.py migrate
```

9. Загрузить фикстуры в БД

```
python manage.py loaddata news.json
```

10. Создать суперпользователя

```
python manage.py createsuperuser
```

11. Запуск проекта, введите команду

```
python manage.py runserver
```

12. Отмена

```
Ctrl + C
```

13. Запуск тестов

```
pytest
```

14. Переход в родительский каталог

```
cd ..
```

15. Переход в директорию ya_note

```
cd ya_note
```

16. Запуск тестов

```
python manage.py test
```

17. Переход в родительский каталог

```
cd ..
```

18. Запустить скрипт для `run_tests.sh` из корневой директории проекта

```
bash run_tests.sh
```

19. Деактивация виртуального окружения

```
deactivate
```
