# Оценка результата проведения AB-тестирования

Задача: провести оценку A\B-тестирования новой рекомендательной системы товаров для пользователей. Оценить изменились ли продажи после внедрения изменений или нет.

## Техническое задание
- Название теста: `recommender_system_test`;
- группы: А — контрольная, B — новая платёжная воронка;
- дата запуска: 2020-12-07;
- дата остановки набора новых пользователей: 2020-12-21;
- дата остановки: 2021-01-04;
- аудитория: 15% новых пользователей из региона EU;
- назначение теста: тестирование изменений, связанных с внедрением улучшенной рекомендательной системы;
- ожидаемое количество участников теста: 6000.
- ожидаемый эффект: за 14 дней с момента регистрации пользователи покажут улучшение каждой метрики не менее, чем на 10%:
    - конверсии в просмотр карточек товаров — событие `product_page`,
    - просмотры корзины — `product_cart`,
    - покупки — `purchase`.

Язык программирования: Python

Основные библиотеки при работе: numpy, pandas, matplotlib, seaborn, plotly, math, stats

В репозитории имеются исходные датафреймы и презентация, включающая основные выводы анализа.
