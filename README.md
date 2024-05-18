# Анализ Upsell-а в кредитовании

**Введение:**

Данное задание посвящено анализу перекрестных продаж (Upsell) в сфере кредитования Тинькофф Банка.

**Цель:**

Определить ключевые факторы, влияющие на выбор клиентом вида кредитования, чтобы оптимизировать процесс Upsell-а.

**Предмет исследования:**

Датасет, содержащий информацию о заявках клиентов на кредитование (226k записей, 211k заявок) с марта 2021 по ноябрь 2022 года.

**Виды кредитования:**

* **Обычный потребительский кредит (КН) (CL):**  Кредит наличными.
* **Кредит наличными под залог автомобиля (КНА) (CLC):** Кредит наличными с залогом автомобиля.
* **Кредит наличными под залог недвижимости (КНН) (CLR):** Кредит наличными с залогом недвижимости.
* **Кредитные карты (КК) (CC):** Револьверный тип кредитования.

**Процесс Upsell:**

* **Downsell:** Продажа более дешевого продукта (КК вместо КН).
* **Upsell:** Продажа более дорогого продукта (КНА вместо КН).

**Процесс согласования условий (СУ):**

* **Дозаполнение залога:**  Возможность перехода на залоговый продукт (КНА или КНН) при подаче заявки на КН.
* **Результат СУ:**
    * **Открытие счета:**  Успешное согласование с указанием типа счета (CL, CLC, CLR).
    * **Unsuccess:** Неуспешное согласование.
* **Активация кредита:**  Успешная активация кредита (success_activate_flg) для получения денег.

**Исследовательский вопрос:**

Какие характеристики клиента определяют наиболее подходящий для него вид кредитования?

**Комментарии к заданию:**

1. Выделить целевую аудиторию (ЦА) для каждого вида кредитования.
2. Определить характеристики клиента, которые могут быть связаны с выбором вида кредитования.
3. Сгруппировать данные на уровне клиентов.
4. Провести анализ Upsell-а: как банк стремится получить максимальную выгоду.
5. Провести анализ данных, чтобы выявить ключевые факторы, влияющие на выбор клиента.
6. Подвести итоги исследования, указав полученные результаты, ограничения, возможности для улучшения.

**Примечание:**

В рамках исследования можно сосредоточиться на отдельных аспектах, исследуя их глубоко.