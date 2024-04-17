
----Стек

- Python 3.10
- Django 5.0

---- Запуск проекта в dev-режиме

1. Клонируйте репозиторий и перейдите в него в командной строке.


2. Установите и активируйте виртуальное окружение:


-python -m venv venv


-source venv/Scripts/activate


3. Установите зависимости из файла requirements.txt:

pip install -r requirements.txt


4. В папке с файлом manage.py выполните миграции:

python manage.py migrate


5. Создайте суперюзера, зайдите в админку:


python manage.py createsuperuser


6. В папке с файлом manage.py запустите сервер, выполнив команду:


python manage.py runserver






