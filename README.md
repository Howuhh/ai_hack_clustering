Решение с хакатона [Ai.Hack](http://aihack.ai-hub.ru)

Kaggle: https://www.kaggle.com/c/ai-hackathon-2018-spb-gpn

Команда:  
- [Alexander Nikolin](https://github.com/Howuhh)  
- [Olga Silyutina](https://github.com/olgasilyutina)  
- [Anna Golovchenko](https://github.com/schatt89)  

## Описание файлов

* train_data.csv - обучающая выборка;
* test_data.csv - тестовая выборка;

## Описание полей

* time - время транцакции;
* date - дата транзакции;
* v_l - объем приобретенного нефтепродукта;
* q - количество приобретенного товара в магазине при АЗС;
* n_tr - номер транзакции;
* sum_b - сумма покупки;
* code_azs - код АЗС, на которой была совершена транзакция;
* id - идентификатор клиента;
* first_prch - дата первой покупки на АЗС;
* location - размещение АЗС (тип локации);
* region - код региона АЗС;
* code - код категории товара;
* code1 - код типа товара;
* percent - скидка в виде бонусов (товар оплачен бонусами);
* type - тип оплаты.


## Задача 2. Газпром Нефть. Кластеризация Клиентов

Проанализируйте и создайте максимально возможное количество сегментов Клиентов на основе покупки нефтепродуктов. Для каждого из выделенных сегментов найдите специфические закономерности потребления сопутствующих товаров и услуг.
 
**Задание состоит из двух частей:**

* Найти максимальное количество закономерностей в покупке нефтепродуктов и разделить клиентов на * сегменты на основе каждой закономерности  
* Внутри сегментов клиентов из пункта 1 найти максимальное количество закономерностей размера и факта покупки/непокупки сопутствующих товаров с детализаций  
 