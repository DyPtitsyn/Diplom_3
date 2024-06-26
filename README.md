## Дипломный проект. Задание 3: UI-тесты

### Автотесты для проверки Stellar Burgers

### Реализованные сценарии тестирования

<span style="color:yellow">test_1_password_recovery</span> - Восстановление пароля <br>
<span style="color:yellow">test_2_personal_account</span> - Личный кабинет <br>
<span style="color:yellow">test_3_main_functionality</span> - Проверка основного функционала <br>
<span style="color:yellow">test_4_orders_feed</span> - Раздел «Лента заказов» <br>

### Структура проекта

<span style="color:yellow">page_objects</span> - все шаблоны проектирования <br>
<span style="color:yellow">conftest.py</span> - все фикстуры <br>
<span style="color:yellow">tests</span> - все тесты <br>
<span style="color:yellow">locators</span> - все локаторы <br>

### Запуск автотестов

**Установка зависимостей**

 <span style="color:yellow">$ pip install -r requirements.txt</span>

**Запуск автотестов**

  <span style="color:yellow">$ pytest -v</span>

**Формирование alure-отчётa в формате html**

 <span style="color:yellow">$ allure serve allure_results</span>