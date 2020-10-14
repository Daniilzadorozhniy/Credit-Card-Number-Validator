# Отчёт о тестировании Credit Card Number Validator
## *Краткое описание*
<07.10.2020> - <08.10.2020> было проведено: 
1. Модульное тестирование;
3. Функциональное тестирование;
- Позитивное тестирование;
- Негативное тестиррвание;

## *На тестирование затрачено*:  3 часа.

## *В результате тестирования выявлены следующие дефекты*:

* [Валидные номера карт состоящие [19] цифр не проходят валидацию #1](https://github.com/Daniilzadorozhniy/Credit-Card-Number-Validator/issues/1)
* [Валидные номера карт состоящие из [14] цифр не проходят валидацию #2](https://github.com/Daniilzadorozhniy/Credit-Card-Number-Validator/issues/2)
* [Валидные номера карт состоящие из [15] цифр не проходят валидацию #3](https://github.com/Daniilzadorozhniy/Credit-Card-Number-Validator/issues/3)

Описание процесса тестирования

## *В процессе тестирования использовались следующие артефакты*:

Баг репорты


## *В качестве тестовых данных использовались данные*- [Генератор валидных номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html) и [Тестовые номера кредитных карт](https://www.kobzarev.com/other/testoviye-nomera-kreditnyh-kart/):

* VISA:

4539663394558602

4929592785373248
* JCB:

3537629913609145050

3538592221315543

* Diners Club - Carte Blanche:

30511556300358

* American Express

378282246310005

47383757405832784

768492645364703875



## *Тестирование производилось в следующем окружении*:

* ОС Windows 7 (Домашняя версия), 64 разрядная
* java -version
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* Браузер Google Chrome (ерсия 81.0.4044.138 (Официальная сборка), (64 бит))
* IntelliJ IDEA v 1.18.7455
