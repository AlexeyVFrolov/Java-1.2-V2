# **Отчёт о тестировании модуля Credit Card Number Validator**
## **Краткое описание**
06.03.2021 - 06.03.2021 было проведено тестирование модуля Credit Card Number Validator. На тестирование затрачено времени: 1 час. В результате выявлены следующие дефекты:
* [Credit Card Number Validator не валидирует номера кредитных карт с количеством цифр, отличным от 16](https://github.com/AlexeyVFrolov/Java-1.2-V2/issues/1)

## **Описание процесса тестирования**
В процессе тестирования использовались следующие артефакты: 
* [Файл с кодом Main.java](https://github.com/AlexeyVFrolov/Java-1.2/blob/master/src/Main.java)

В качестве тестовых данных использовались данные:
* Валидные номера карт ([FREEFORMATTER.COM](https://www.freeformatter.com/credit-card-number-generator-validator.html))
    * 4539841818435870523
    * 378944768079785

Тестирование производилось в следующем окружении:
* ОС Windows 10, 64-разрядная
* Java v. 11.0.10
* IntelliJ IDEA Community Edition 2020.3.2