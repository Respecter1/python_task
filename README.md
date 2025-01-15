# TODO MANAGER

ToDo Manager — це веб-додаток для управління завданнями, розроблений на Django з використанням Django REST Framework.

## ЕТАПИ РОБОТИ

1. **Клонування репозиторію:**
   ```bash
   git clone https://github.com/Respecter1/python_task.git
   cd python_task
   ```

2. **Створення віртуального середовища:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Встановлення залежностей:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Виконання міграцій:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Створення суперкористувача:**
   - Ввів логін, email і пароль:
   ```bash
   python manage.py createsuperuser
   ```

6. **Запуск сервера:**
   ```bash
   python manage.py runserver
   ```

7. **Перевірка:**
   - **Адмін-панель:** `http://127.0.0.1:8000/admin/`
   - **API:** `http://127.0.0.1:8000/api/tasks/`
     
8. **Додав '.gitignore':**
   - Додав файл `.gitignore`, щоб видалити зайві файли (`venv/`, `db.sqlite3`) з репозиторію.
   - Довантажив до репозитроію 



