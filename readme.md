# Бухгалтерия для фрилансера
---
Привет, собрат!
В последнее время много занимаюсь «вольными хлебами», что побудило меня в свою очередь сдеать вот такой [документ](https://docs.google.com/spreadsheets/d/1DNyqy74zbxTP2QF7-Akf-D7trM1ObLdZjc51m535VWM/edit#gid=1971514422) для учета прогресса по проекту, а также наглядно показывало б сколько и когда денег приходит.
Это удобно заказчикам и тебе. Они видят когда и сколько ты работаешь, ты видишь когда и сколько денег от них приходит. Лепота!

## Как пользоваться
---
Пользоваться этой таблицей проще простого:
- пройди по [ссылке](https://docs.google.com/spreadsheets/d/1DNyqy74zbxTP2QF7-Akf-D7trM1ObLdZjc51m535VWM/edit#gid=1971514422);
- авторизуйся в Google, если не авторизован;
- сохрани себе копию документа (Файл → Создать копию);
- хаполни таблицу PriceList;
- а далее по проекту, пиши даты, тип работ, затраченное время, а сумма будет считаться автоматически, а также отображаться в таблице Summary;
- ах, да… не забыай заполнять таблицу Income, когда приходят платежи, чтоб все было по-честному

## Примеры
---
Таблица `PriceList`
| Тип работ | Стоимость в час |
| --------- | ----------------|
| Консультирование | 1 000,00 ₽ |
| Разработка | 1 200,00 ₽ |

Учтите, что все ячейки с финансами форматируются как денежная единица выраженная в российских рублях. Можете прикрутить конвертор валют, если хотите, мне не понадобилось.

Таблица `Progress`
| Дата | Тип работ | Время | Git commit |   | Сумма |
| ---- | --------- | ----- | ---------- | - | ----- |
| 14 февраля 2017 | Разработка | 1 | 65fc178 |  | 1 200,00 ₽ |

Ячейка `Дата` форматирована как дата, поэтому в даном примере я просто написал 14.02. Ячейка `Тип работ` генерируется из списка работ таблицы `PriceList` и представляет собой dropDown меню, после того, как укажите количество часов (именно в часах, поэтому 30 минут это 0,5) сумма в денежном эквиваленте автоматически посчитается. `Git commit` опоционально, можно просто удалить, но я держу ее для того, чтобы клиент мог реально посмотреть на объем кода.

Таблица `Income`
| Дата | Сумма |
| ---- | ----- |
| 14 февраля 2017 | 7 110,00 ₽ |

Здесь по ячейкам также как и выше.

Таблица `Summary`
Полностью автоматическая таблица, которая считает сколько денег пришло и сколько еще должны и общую стоимость проекта

---
Удачи и творческих успехов!

## Лицензия
Copyright (c) 2017 Aziz Zainutdin

Данная лицензия разрешает лицам, получившим копию данного программного обеспечения и сопутствующей документации (в дальнейшем именуемыми «Программное Обеспечение»), безвозмездно использовать Программное Обеспечение без ограничений, включая неограниченное право на использование, копирование, изменение, слияние, публикацию, распространение, сублицензирование и/или продажу копий Программного Обеспечения, а также лицам, которым предоставляется данное Программное Обеспечение, при соблюдении следующих условий:

Указанное выше уведомление об авторском праве и данные условия должны быть включены во все копии или значимые части данного Программного Обеспечения.

ДАННОЕ ПРОГРАММНОЕ ОБЕСПЕЧЕНИЕ ПРЕДОСТАВЛЯЕТСЯ «КАК ЕСТЬ», БЕЗ КАКИХ-ЛИБО ГАРАНТИЙ, ЯВНО ВЫРАЖЕННЫХ ИЛИ ПОДРАЗУМЕВАЕМЫХ, ВКЛЮЧАЯ ГАРАНТИИ ТОВАРНОЙ ПРИГОДНОСТИ, СООТВЕТСТВИЯ ПО ЕГО КОНКРЕТНОМУ НАЗНАЧЕНИЮ И ОТСУТСТВИЯ НАРУШЕНИЙ, НО НЕ ОГРАНИЧИВАЯСЬ ИМИ. НИ В КАКОМ СЛУЧАЕ АВТОРЫ ИЛИ ПРАВООБЛАДАТЕЛИ НЕ НЕСУТ ОТВЕТСТВЕННОСТИ ПО КАКИМ-ЛИБО ИСКАМ, ЗА УЩЕРБ ИЛИ ПО ИНЫМ ТРЕБОВАНИЯМ, В ТОМ ЧИСЛЕ, ПРИ ДЕЙСТВИИ КОНТРАКТА, ДЕЛИКТЕ ИЛИ ИНОЙ СИТУАЦИИ, ВОЗНИКШИМ ИЗ-ЗА ИСПОЛЬЗОВАНИЯ ПРОГРАММНОГО ОБЕСПЕЧЕНИЯ ИЛИ ИНЫХ ДЕЙСТВИЙ С ПРОГРАММНЫМ ОБЕСПЕЧЕНИЕМ.