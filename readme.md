# Наука о данных

Совместный бакалавриат ВШЭ-РЭШ, 2-й курс.

**Лектор:** Никита Честнов

**Семинаристы:**
- Лавприт Сингх-Пальчевская
- Владислав Фомберг
- Никита Честнов

## План курса

>**Примечание**
> 
> План курса в процессе доработки, темы конкретных занятий могут меняться

| №   | Дата          | Тема занятия                                                                       |
|-----|---------------|------------------------------------------------------------------------------------|
| 01  | 13.01         | Знакомство с Python. Основные инструменты разработки                               |
| 02  | 16.01 / 19.01 | Базовые типы данных - практика. Базовый ввод / вывод. Условный оператор            |
| 03  | 20.01         | Контейнеры. Списки, кортежи, словари, множества                                    |
| 04  | 23.01 / 24.01 | Циклы `for` и `while`                                                              |
| 05  | 27.01         | Строки. Работа с файлами                                                           |
| 06  | 30.01 / 31.01 | Функции (часть 1). Базовый синтаксис, генераторы                                   |
| 07  | 06.02 / 09.02 | Функции (часть 2). Области видимости, замыкания, декораторы                        |
| 08  | 10.02         | ООП. Основные принципы и определения и базовый синтаксис                           |
| 09  | 13.02 / 14.02 | ООП. Magic-методы. Декораторы для классов                                          |
| 10  | 17.02         | Дополнительные темы Python. *Юнит-тестирование*. Обработка ошибок. Модули и пакеты |
| 11  | 20.02 / 21.02 | Регулярные выражения                                                               |
| 12  | 27.02 / 28.02 | Numpy                                                                              |
| 13  | 03.03         | Оптимизация кода. Введение в Cython. Numba                                         |
| 14  | 06.03 / 07.03 | Введение в Pandas                                                                  |
| 15  | 10.03         | Продвинутый Pandas                                                                 |
| 16  | 13.03 / 14.03 | Визуализация данных. Matplotlib                                                    |
| 17  | 17.03         | Web 101. Парсинг страниц. BeautifulSoup                                            |
| 18  | 20.03 / 21.03 | Символьные вычисления. Библиотека SymPy                                            |
| 19  | 24.03         | Продвинутый парсинг. Scrapy. Selenium                                              |
| 20  | 03.04 / 04.04 | Серверные приложения. Streamlit                                                    |
| 21  | 07.04         | Работа с графовыми данными. NetworkX                                               |
| 22  | 10.04 / 11.04 | Введение в базы данных. SQLite                                                     |
| 23  | 14.04         | Работа с геоданными. GeoPandas. Shapely. Folium                                    |
| 24  | 17.04 / 18.04 | TBD                                                                                |
| 25  | 21.04         | R                                                                                  |
| 26  | 24.04 / 25.04 | R                                                                                  |
| 27  | 28.04         | R                                                                                  |
| 28  | ---           | R                                                                                  |
| 29  | ---           | TBD                                                                                |
| 30  | ---           | TBD                                                                                |

>**Примечание** - темы, выделенные курсивом, являются приблизительными 

Планируемые библиотеки (+потенциальные библиотеки):
- sklearn
- командная строка и Unix Shell

## Оценивание на курсе

Источники баллов для оценки:
1. **Тесты на лекциях** - заполнение гугл-форм, выбор из нескольких вариантов ответов
2. **Контесты по программированию на Python** - решение задач с автоматической проверкой, **скатанная задача карается домножением баллов за нее на -1**
3. **Финальный проект** - Work In Progress, примерная версия - [версия прошлого года](http://math-info.hse.ru/2021-22/%D0%9D%D0%B0%D1%83%D0%BA%D0%B0_%D0%BE_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/%D0%98%D1%82%D0%BE%D0%B3%D0%BE%D0%B2%D1%8B%D0%B9_%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82)

### Формула оценки за курс

#### Оценка за Python

- Оценка за тесты: 
  $$T = 10 \cdot \frac{1}{N} \sum_{i=1}^N t_i / \max t_i = \frac{10}{5} \left( \frac{t_1}{9} + \frac{t_2}{10} + \frac{t_3}{10} + \frac{t_4}{10} + \frac{t_5}{8} \right),$$
  где $t_i$ - балл за $i$-й тест, $\max t_i$ - максимальная оценка за $i$-й тест.
- Оценка за контесты: 
  $$C = 10 \cdot \frac{1}{M} \sum_{i=1}^M c_i / \max c_i = \frac{10}{3} \left( \frac{c_1}{10} + \frac{c_2}{18} + \frac{c_3}{30} \right),$$
  где $c_i$ - балл за $i$-й контест, $\max c_i$ - максимальная оценка за $i$-й контест (3й контест = лабораторка по криптовалютам).
  Да, макс. балл за 3й контест - 30.
- Оценка за проект:
  $$P = 10\cdot\frac{p}{17},$$
  где $p$ - сумма баллов за проект. Да, максимальное значение суммы согласно таблице ниже 22, а делится на 17.

Оценка за Python:

$$Python = 0.1 \cdot T + 0.4 \cdot C + 0.5 \cdot P,$$

где $round$ - функция математического округления.

#### Оценка за R

Оценка за R:

$$ R = 10 \cdot \frac{T + HW_1 + HW_2 + B}{50}, $$

где:
- $T$ - оценка за тест, макс. - 10
- $HW_i$ - оценка за $i$-е ДЗ, макс. - 20 (за каждое)
- $B$ - бонус за активность на занятиях, макс. - 10

Да, в сумме максимум 60, а делим на 50.

#### Итоговая оценка за курс

$$ Mark = round(0.75 \cdot Python + 0.25 \cdot R), $$

где $round$ - математическое округление.

## Финальный проект

### Основные пункты

- Проекты выполняются индивидуально и самостоятельно
- Любое использование чужого кода должно быть явно отмечено с помощью следующих комментариев:
  - начало чужого кода - `### FROM: (адрес источника)`
  - конец чужого кода - `### END FROM`
- **Дедлайн** - вторая половина мая (ближе к тому времени будет более точная дата)

### Оценивание проекта

| Критерий                                                 | Баллы                                                                                                                                                                                                                                                   |
|----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Общее. Объём                                             | Объём проекта измеряется в «осмысленных самостоятельно написанных логических строках кода»<br><ul><li>**1** — 120 строк и больше.</li></ul>                                                                                                             |
| Общее. Целостность проекта                               | <ul><li>**0** — проект выглядит как набор несвязанных компонент</li><li>**1** — проект выглядит целостным, все технологии используются по делу</li></ul>                                                                                                |
| Общее. Наличие хорошей документации                      | <ul><li>**0** — документация отсутствует или чисто номинальная</li><li>**1** — качественная документация, все компоненты проекта описаны</li></ul>                                                                                                      |
| Общее. Качество кода                                     | <ul><li>**0** — сложно прочитать код, непонятные имена переменных, странный синтаксис</li><li>**1** — великолепная читаемость, стиль практически по [PEP8](https://pythonworld.ru/osnovy/pep-8-rukovodstvo-po-napisaniyu-koda-na-python.html)</li></ul> |
| Общее. Впечатление от проекта                            | <ul><li>**0** — ну ок, среднестатистический проект</li><li>**1** — вау, круто!</li></ul>                                                                                                                                                                |
| Получение данных. Работа с REST API (XML/JSON)           | <ul><li>**1** — использовались API примерно в объеме задач домашней работы</li><li>**2** — нетривиальное использование API, использование недокументированного API</li></ul>                                                                            |
| Получение данных. Веб-скреппинг                          | <ul><li>**1** — использовался базовый веб-скреппинг с помощью beautifulsoup</li><li>**2** — использовались более сложные технологии скреппинга (Selenium, scrapy)</li></ul>                                                                             |
| Обработка данных. Pandas                                 | <ul><li>**1** — базовое применение</li><li>**2** — использовались продвинутые возможности pandas (группы, окна, трансформации)</li></ul>                                                                                                                |
| Регулярные выражения (для случаев, когда без них тяжело) | <ul><li>**1** — использовались</li></ul>                                                                                                                                                                                                                |
| Математические возможности Python                        | <ul><li>**1** — содержательное использование numpy/scipy, SymPy и т.д. для решения математических задач</li></ul>                                                                                                                                       |
| Работа с геоданными                                      | <ul><li>**1** — использовались geopandas, shapely, folium и т.д.</li></ul>                                                                                                                                                                              |
| Работа с графами                                         | <ul><li>**1** — использовалась библиотека networkx</li></ul>                                                                                                                                                                                            |
| Визуализация данных                                      | <ul><li>**1** — использовались базовые визуализации типа «построен scatter plot»</li><li>**2** — более сложные визуализации, требующие написания нетривиального кода</li></ul>                                                                          |
| SQL                                                      | <ul><li>**1** — использовался</li></ul>                                                                                                                                                                                                                 | 
| Демонстрация проекта. Streamlit                          | <ul><li>**1** — имеется демонстрация с помощью streamlit, которую нужно запускать вручную</li><li>**2** - streamlit-проект размещён в интернете (скачивать ничего не надо, достаточно пройти по ссылке и всё запустится)</li></ul>                                                                                                                |
| Машинное обучение                                        | <ul><li>**1** — построение предсказательных моделей типа регрессий или решающих деревьев</li></ul>                                                                                                                                                      |
| Дополнительные технологии                                | Классные библиотеки/программы, не обсуждавшиеся в ходе курса<br><ul><li>**1** —  использовались на уровне «взять пример из документации и адаптировать для своих нужд»</li><li>**2** — использовались на продвинутом уровне</li></ul>                   |

### Проекты прошлых лет

На странице курса прошлого года опубликованы лучшие (по результату peer review) проекты - можете использовать их для вдохновения.

Нужно иметь в виду, что там были другие требования (другой набор технологий), и это был проект за один модуль, а не за два.

