# Отчёт о тестировании Money Transfer

## Краткое описание

27.11.2021 - 21.11.21 было проведено тестирование кода на пополнение счёта клиентом приложения Money Transfer.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/Valery-Buz/Java-1-homework/issues/1#issue-1065125440

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Баг-репорт 

В качестве тестовых данных использовались данные:
* текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000
* сумма перевода - переменная типа int, значение - 500_000_000
* переменная для хранения итогового значения - тип int

Тестирование производилось в следующем окружении:
* Windows 10 (х64)
* Java 11.0.13+8 (х64)

