Кофемашина на Python с использованием многозадачности и MongoDB
Этот проект представляет собой простую кофемашину, написанную на Python с использованием объектно-ориентированного программирования (ООП), многозадачности (threading) и базы данных MongoDB для хранения информации о доступных видах кофе и их ценах.

Особенности проекта:
MongoClient: Класс для взаимодействия с базой данных MongoDB. Используется для хранения информации о видах кофе и их ценах.

CoffeeMachine: Класс, представляющий кофемашину. Каждый заказ обрабатывается в отдельном потоке с использованием многозадачности.

Customer: Класс, представляющий клиента. Каждый клиент создает свой поток для размещения заказа.

Зависимости:
Python 3.x
MongoDB
pymongo (можно установить с помощью pip install pymongo)
Запуск проекта:
Установите MongoDB на своем компьютере и убедитесь, что сервер запущен.

Установите зависимости:

bash
Copy code
pip install pymongo
Запустите основной скрипт:

bash
Copy code
python имя_скрипта.py
Примечание:
Проект имитирует работу кофемашины с использованием многозадачности. Каждый клиент представляет собой поток, который размещает заказ на кофе.

Для имитации приготовления кофе используется функция time.sleep(2).

Проект создан с целью демонстрации принципов ООП, многозадачности и взаимодействия с базой данных MongoDB в контексте простой кофемашины.






