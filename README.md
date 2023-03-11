# HW-28.1

Итоговый проект по автоматизации тестирования

Заказчик передал вам следующее задание:

Протестировать требования.
Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.
Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.
Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов)

Для тестирования сайта были использованы:
техники эквивалентного разбиения, причина/следствие
анализ граничных значений

Тесты настроены на запуск через терминал python -m pytest -v --driver Chrome --driver-path chromedriver.exe tests_SF_RT.py

base_data.py - базовые классы, процедуры, функции и локаторы для автотестов

settings.py - регистрационные данные для позитивных тестов авторизации

tests_SF_RT.py - набор автотестов

Объект тесирования: форма регистрации/авторизации сайта: https://b2c.passport.rt.ru

Ссылка на тестирование требований, тест-кейсы, баг-репорты: https://docs.google.com/spreadsheets/d/1j4-ZqqL5zM8w_LJLt82pv-d2RYZfvIq8QbqICzSPnI0/edit?usp=sharing
