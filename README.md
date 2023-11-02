## Окружение
- Операционная система: Windows 10 Версия 115.0.5790.171 (Официальная сборка), (64 бит)

## Для запуска тестов:

1. Установите необходимые библиотеки, выполнив команду:
   ```shell
   pip install -r requirements.txt
   ```

2. Скачайте вебдрайвер Chrome с сайта https://chromedriver.chromium.org/ и поместите его в корневую директорию проекта.

3. Выполните запуск тестов через команду:
```shell
python -m pytest -v tests/test.py
```

## Файлы проекта:

### Корневой каталог:
- `config.py` - содержит переменные, используемые в проекте.
- `README.md` - содержит информацию в целом о проекте.
- `requirements.txt` - содержит все библиотеки и зависимости проекта.

### Директория `tests`:
- `conftest.py` - условия для запуска браузера.
- `test.py` - автотесты по проекту.
- `chromedriver.exe` - файл драйвера для Chrome версии 115.0.5790.171.

### Директория `pages`:
- `Base_page.py` - основные методы работы со страницей.
- `Main_page.py` - локаторы по проекту.

## Требования по проекту:
- [Требования по проекту](https://docs.google.com/document/d/1EWzdempFEOzzNnDM9YgcN2akToniXR03RgFhNEzf8IQ/edit?usp=sharing)

## Объект тестирования:
- [https://b2c.passport.rt.ru](https://b2c.passport.rt.ru)

## Ответы на задание:

- Разработано 20 тест-кейсов.
- Написано 20 автотестов (по одному автотесту на каждый написанный тест-кейс).

## Техники тест-дизайна, используемые в проекте:
1. Эквивалентное разбиение.
2. Предугадывание ошибок.
3. Анализ граничных значений.

## Инструменты тестирования:
- Google Docs - для составления тест-кейсов.
- PyCharm - для написания и запуска автотестов.
- Google Chrome - для запуска автотестов.

## Запуск тестов:

Для запуска тестов необходимо установить все библиотеки, указанные в файле `requirements.txt`, скачать соответствующий вашему окружению вебдрайвер для Chrome с сайта [https://chromedriver.chromium.org/](https://chromedriver.chromium.org/) и выполнить запуск через команду:
```shell
python -m pytest -v tests/test.py
```

Проект выполнен на Windows 10 с браузером Chrome версии 115.0.5790.171 (Официальная сборка), (64 бит).

## Для запуска определенного теста можно использовать:

1. `python -m pytest -v tests/test.py::test_main_logo`
2. `python -m pytest -v tests/test.py::test_invalid_auth_mail`
3. `python -m pytest -v tests/test.py::test_invalid_auth_mail`
4. `python -m pytest -v tests/test.py::test_pass_invalid_auth_parol`
5. `python -m pytest -v tests/test.py::test_pass_invalid_auth_mail`
6. `python -m pytest -v tests/test.py::test_pass_invalid_auth_mail`
7. `python -m pytest -v tests/test.py::test_forgot_password`
8. `python -m pytest -v tests/test.py::test_back_button`
9. `python -m pytest -v tests/test.py::test_click_check_in`
10. `python -m pytest -v tests/test.py::test_check_in`
11. `python -m pytest -v tests/test.py::test_check_in_false_email`
12. `python -m pytest -v tests/test.py::test_check_in_false_mobile_max`
13. `python -m pytest -v tests/test.py::test_check_in_false_mobile_mini`
14. `python -m pytest -v tests/test.py::test_check_in_false_name_mini`
15. `python -m pytest -v tests/test.py::test_check_in_name_two_letters`
16. `python -m pytest -v tests/test.py::test_check_in_name_thirty_letters`
17. `python -m pytest -v tests/test.py::test_check_in_name_thirty_one_letters`
18. `python -m pytest -v tests/test.py::test_click_ok`
19. `python -m pytest -v tests/test.py::test_click_mail`
20. `python -m pytest -v tests/test.py::test_click_ya`
