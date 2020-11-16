# tech-highload-hw2
## Тема
Приложение с расписанием.  
Пользователи могут создавать своё уникальное расписание, при необходимости и желании используя готовые (если нужные есть в базе данных приложения).
## Возможный диапазон нагрузок
По данным статистического сборника «Образование в цифрах: 2020», выпущенного институтом статистических исследований и экономики знаний НИУ ВШЭ, в России на начало 2019/20 учебного года 16 565 600 школьников и 4 068 300 студентов. Предположим, 4% школьников и 100% студентов заинтересовались приложением. Получается 4 730 924 уникальных пользователей ежедневно (по будням как минимум).
## Планируемая нагрузка
Будем исходить из того, что каждый пользователь заходит в приложение в среднем 9 раз в день. В период с 8:00 до 18:00 нагрузка средняя. С 18:00 до 21:00 пивковая: все заходят посмотреть домашку. С 21:00 до 8:00 следующего дня заметно падает. Получается пиковая (вечерняя) нагрузка примерно 4000 rps. Будем обеспечивать 5000 rps.
## Логическая схема базы данных
## Физическая системы хранения
## Прочие технологии
## Расчет нагрузки и потребного оборудования
## Выбор хостинга / облачного провайдера и расположения серверов
## Схема балансировки нагрузки
## Обеспечение отказоустойчивости
