# Отчёт о тестировании Credit Card Number Validator
## *Краткое описание*
<07.10.2020> - <08.10.2020> было проведено: 
1. Модульное тестирование;
3. Функциональное тестирование;
- Позитивное тестирование;
- Негативное тестиррвание;

## *На тестирование затрачено*:  3 часа.

## *В результате тестирования выявлены следующие дефекты*:

* [Валидные ключи не прошли валидацию в KeyValidator #1](https://github.com/Daniilzadorozhniy/KeyValidator/issues/1#issue-715875866)
* [Невалидный ключ 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 прошел валидацию в KeyValidator #2](https://github.com/Daniilzadorozhniy/KeyValidator/issues/2#issue-715882528)

Описание процесса тестирования

## *В процессе тестирования использовались следующие артефакты*:

Баг репорты

[Чек лист](https://github.com/Daniilzadorozhniy/Test-case.git)

## *В качестве тестовых данных использовались данные*- [Генератор валидных номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html):

* VISA:
4539663394558602
* JCB:
3537629913609145050
* Diners Club - Carte Blanche:
30511556300358

## *Тестирование производилось в следующем окружении*:

* ОС Windows 7 (Домашняя версия), 64 разрядная
* java -version
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* Браузер Google Chrome (ерсия 81.0.4044.138 (Официальная сборка), (64 бит))
* IntelliJ IDEA v 1.18.7455