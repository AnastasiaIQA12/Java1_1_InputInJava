## Тест-кейс №2 - "Внесение невалидных ключей"
**Описание:** проверка приложения на ввод невалидных ключей

**Предыстория:** откройте командную строку

**Шаги**

1 Запустите приложение из командной строки, набрав команду java KeyValidator

2 Введите невалидные номера ключей:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

3 Нажмите Enter и ждите результата программы

**Ожидаемый результат:**
приложение выведет следующую информацию:
* Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL