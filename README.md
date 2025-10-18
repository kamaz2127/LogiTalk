# LogiTalk
-
1. Переходимо в папку з LogiTalk
cd D:\Python\LogiTalk  - змініть шлях на ту папку, де лежать client.py і server.py

2. Створюємо віртуальне середовище
python -m venv venv  - створює папку venv для локальних бібліотек

3. Активуємо віртуальне середовище
# Для PowerShell (якщо буде помилка про виконання скриптів, виконайте команду нижче)
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process

venv\Scripts\Activate.ps1  - активуємо venv

# 4. Встановлюємо потрібні бібліотеки
pip install customtkinter pillow  - customtkinter для графіки, pillow для зображень

# 5. Запускаємо клієнт 
python client.py  - відкриває вікно LogiTalk
# Вводимо:
# Ім’я (нік)
# Хост: 
# Порт: 8082
# Натискаємо "Приєднатися"


