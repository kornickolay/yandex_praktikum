### Анализ пользовательского поведения в мобильном приложении.

Описание данных:

##### Таблица exp:
- *EventName* — название события
- *DeviceIDHash* — уникальный идентификатор пользователя
- *EventTimestamp* — время события
- *ExpId* — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

Пункты и цели исследования:

- Открыть файлы с данными и изучить общую информацию.
- Предобработка данных.
- Изучение и проверка данных. Построение графика распределения событий по дате и времени с помощью библиотеки Matplotlib.
- Изучение воронки событий. Построение графиков с помощью библиотеки Plotly.
- Проверка гипотез (20 межгрупповых тестов для всех событий) о равенстве статистической значимости на основе z-тестов и библиотек NumPy и SciPy.
