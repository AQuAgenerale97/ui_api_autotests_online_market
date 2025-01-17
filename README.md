# Проект по UI-тестированию интернет-магазина <a target="_blank" href="https://www.online-market.by/keyboards">Online-Market</a>

![main page screenshot](pictures/online_market_main_page.png)

---
### Список проверок, реализованных в UI-автотестах
1. Открытие первого монитора в списке.
2. Проверка фильтра "Диагональ" значение "15.6".
3. Добавление монитора в корзину.
4. Удаление монитора из корзины.
5. Добавление монитора в список сравнения.
6. Удаление монитора из списка сравнение.
7. Очистка списка сравнения.
8. Добавление монитора в избранное.
9. Удаление монитора из избранного.
10. Очистка списка избранного.

---

### Используемые инструменты
<img title="Python" src="pictures/icons/python.svg" height="40" width="40"/> <img title="Pytest" src="pictures/icons/pytest.svg" height="40" width="40"/> <img title="Allure Report" src="pictures/icons/allure_report.png" height="40" width="40"/> <img title="GitHub" src="pictures/icons/github.svg" height="40" width="40"/> <img title="Selenoid" src="pictures/icons/selenoid.png" height="40" width="40"/> <img title="Selene" src="pictures/icons/selene.png" height="40" width="40"/> <img title="Pycharm" src="pictures/icons/pycharm-original.svg" height="40" width="40"/> <img title="Telegram" src="pictures/icons/telegram.png" height="40" width="40"/> <img title="Jenkins" src="pictures/icons/jenkins-original.svg" height="40" width="40"/> <img title="Allure TestOps" src="pictures/icons/allure_testops.svg" height="40" width="40"/>

---

### Запуск автотестов осуществляется с использованием Jenkins
> [Ссылка на сборку в Jenkins](https://jenkins.autotests.cloud/job/Slinkov_online_market_ui_autotests/)

#### Для запуска автотестов в Jenkins
1. Открыть [задачу в Jenkins](https://jenkins.autotests.cloud/job/Slinkov_online_market_ui_autotests/)

![jenkins job main page](pictures/Jenkins_job_main_page.jpg)

2. Нажать "**Build Now**".

---

### Интеграция с Allure TestOps

> [Тест-кейсы](https://allure.autotests.cloud/project/4573/test-cases?treeId=0)

![allure_testops test_cases](pictures/allure_testops_test_cases.jpg)

---

#### Интеграция с Jira
![This is an image](pictures/jira_ui.png)

---

### Уведомления в Телеграм

![telegram_notification](pictures/tg_notification.jpg)

---

### Прохождение автотеста

![autotest](pictures/del_display_in_compare_page.gif)
