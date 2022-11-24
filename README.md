# О ПРОЕКТЕ

Проект PANDAS_session считывает данные из файла file1.csv, который содержит данные по просмотрам товаров на сайте [“customer_id”, “product_id”, “timestamp”] и преобразоывает их так, что просмотры одного customer_id разбиваются на сессии (появления на сайте). Сессией считаются все смежные просмотры, между которыми не более 3 минут.

# ИСПОЛЬЗУЕМЫЕ ТЕХНОЛОГИИ

python, PANDAS

# Как запустить проект:

1. Клонировать репозиторий и перейти в него в командной строке:

```
git@github.com:irinaexzellent/PANDAS_sessions.git
```

2. Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```
```
source venc/Scripts/activate
```

3. Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```

4. Выполнить:
```
jupyter notebook
```

# Автор

* **Ирина Иконникова** -  [IrinaIkonnikova](https://github.com/irinaexzellent)

