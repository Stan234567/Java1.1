# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

14/04/22 - 14/04/22 был проведен "Тестовый сценарий" в приложения IntelliJ IDEA.


В результате тестирования выявлены следующие дефекты:

Карты менее 16 символов не проходят верификацию :

![False](https://user-images.githubusercontent.com/89197421/163427317-c8f942c4-0d3d-4782-9a3b-1b7a67dfa7be.jpg)
![F2](https://user-images.githubusercontent.com/89197421/163427427-ae62f5e2-4e2e-44af-933e-da739e45a1dc.jpg)

Карты 16 символов проходят верификацию : 
![True](https://user-images.githubusercontent.com/89197421/163428069-84b802c4-8ab4-4d0a-831d-4cbf329c3e0e.jpg)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Тестовый сценарий(тест) https://github.com/Stan234567/Java1.1/issues/1 



В качестве тестовых данных использовались данные :
https://www.getcreditcardnumbers.com/
* American Express - 379766284310389
* American Express - 345802878081812
* American Express - 345634105129084

**Окружение:
Выпуск	Windows 10 Pro
Версия	21H2
Дата установки	‎10.‎08.‎2021
Сборка ОС	19044.1526
Windows Feature Experience Pack 120.2212.4170.0
OpenJDK 11.0.14**
