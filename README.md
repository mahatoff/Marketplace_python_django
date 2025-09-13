Django Project
📌 О проекте
Это веб-приложение на Django.  
Проект реализует базовый функционал для маркетплейса электронных товаров

🚀 Технологии
- Python 3.9.7 
- Django 3.2.8 
- SQLite
- HTML / CSS / JavaScript  

⚙️ Установка и запуск
1. Клонировать репозиторий
```bash
git clone https://github.com/mahatoff/Marketplace_python_django.git
cd project_name
```

3. Создать виртуальное окружение
```bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
```
4. Установить зависимости
```bash
pip install -r requirements.txt
```
5. Применить миграции
```bash
python manage.py migrate
```
6. Создать суперпользователя
```bash
python manage.py createsuperuser
```
7. Запустить сервер разработки
```bash
python manage.py runserver
```
После запуска проект будет доступен по адресу:
http://127.0.0.1:8000/
