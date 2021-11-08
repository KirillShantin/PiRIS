<table style="width: 100%;">
  <tr>
    <td style="text-align: center; border: none;"> 
        Министерство образования и науки РФ <br/>
        ГБПОУ РМЭ "Йошкар-Олинский Технологический колледж 
    </td>
  </tr>
  <tr>
    <td style="text-align: center; border: none; height: 45em;">
        <h2>
            Курс лекций по предмету <br/>
            "Проектирование и разработка информационных систем"
        <h2>
    </td>
  </tr>
  <tr>
    <td style="text-align: right; border: none; height: 20em;">
        <div style="float: right;" align="left">
            <b>Разработал</b>: <br/>
            Колесников Евгений Иванович
        </div>
    </td>
  </tr>
  <tr>
    <td style="text-align: center; border: none; height: 1em;">
        г.Йошкар-Ола, 2021
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

# https://github.com/kolei/PiRIS

# Содержание

<!-- 

TODO

https://dev.mysql.com/downloads/windows/installer/8.0.html

- ERD
- SQL: основы, триггеры, представления
- импорт данных
- сервер АПИ на PHP
- сетевые запросы C#, Kotlin (встроенными средствами)

- Паттерны для новичков: MVC vs MVP vs MVVM https://habr.com/ru/post/215605/

- что-то про интеграционное тестирование https://pozitivmag.ru/aksessuary/vidy-testirovaniya-i-podhody-k-ih-primeneniyu-integracionnoe/


https://docs.microsoft.com/ru-ru/visualstudio/test/isolating-code-under-test-with-microsoft-fakes?view=vs-2019

https://habr.com/ru/post/151185/

http://sergeyteplyakov.blogspot.com/2014/01/microsoft-fakes-state-verification.html

 -->

* [МДК. 05.01 Проектирование и дизайн информационных систем](#МДК-0501-Проектирование-и-дизайн-информационных-систем)

* [МДК. 05.02 Разработка кода ИС](#МДК-0502-Разработка-кода-ИС)

* [МДК. 05.03 Тестирование информационных систем](#МДК-0503-Тестирование-информационных-систем)

# МДК. 05.01 Проектирование и дизайн информационных систем

<!-- 56+92=148, 34+72=106 -->

## Тема 5.1.1. Основы проектирования информационных систем

<!-- https://sites.google.com/site/anisimovkhv/learning/pris/lecture -->

### Лекции

1. [Основные понятия и определения ИС.](articles/5_1_1_1_intro2.md)
    
2. [Анализ предметной области. Основные понятия системного и структурного анализа.](articles/5_1_1_4_analiz.md)

3. [Диаграмма вариантов использования (прецедентов, use case)](articles/5_1_1_10_uml_use_case.md)

4. [Спецификация вариантов использования (прецедентов)](articles/5_1_1_10_uml_uc_spec.md)

### Контрольные вопросы

* назовите основные элементы диаграммы прецедентов
* Что такое **данные**?
* Что такое **информационная система**?

## Тема 5.1.2. Проектирование баз данных

### Лекции

1. [Основы проектирования баз данных.](articles/5_1_1_1_erd2.md)

2. [Словарь данных](articles/5_1_1_1_data_dictionary.md)

3. [Создание ER-диаграммы в среде MySQL Workbench](articles/5_1_1_1_erd_workbench.md)

4. [Основы SQL](./articles/sql_for_beginner.md)

<!-- 
В "основы" добавить 
- count и функции работы со временем (between)  
- UPDATE, DELETE 
-->

5. [Создание базы данных. Импорт данных.](./articles/sql_import.md)

### Контрольные вопросы

* Что такое **домен**?
* Что входит в классическую ER-диаграмму?
* Какие виды **ключей** Вы знаете?
* Назовите этапы проектирования БД.

## Тема 5.1.3. C# и MySQL.

1. [Создание подключения к БД MySQL. Получение данных с сервера.](./articles/cs_mysql_connection2.md)

2. [Вывод данных согласно макету (ListView, Image).](./articles/cs_layout.md)

3. [Пагинация, сортировка, фильтрация, поиск](./articles/cs_pagination.md)

4. [Подсветка элементов по условию. Дополнительные выборки.Массовая смена цены продукции.](./articles/cs_coloring.md)

5. [Создание, изменение продукции](./articles/cs_edit_product.md)

## Тема 5.1.4. Разработка мобильных приложений. Android Studio. Kotlin.

1. [Основы языка Kotlin](./articles/kotlin.md)

2. [Первый проект в Android Studio](./articles/android_studio.md)

3. [Стили и темы. Ресурсы. Фигуры. Обработчики событий.](./articles/themes.md)

<!--

https://office-menu.ru/uroki-sql Уроки SQL

2. [Жизненный цикл информационных систем.](articles/5_1_1_2_lifecycle.md)

[4+0 => 8+0]: _

3. [Организация и методы сбора информации.](articles/5_1_1_3_get_info.md)


[4+0 => 12+0]: _


[4+0 => 16+0]: _

5. [Постановка задачи обработки информации. Основные виды, алгоритмы и процедуры обработки информации, модели и методы решения задач обработки информации.](articles/5_1_1_5_obr_inf.md)

[6+0 => 22+0]: _

6. [Основные модели построения информационных систем, их структура, особенности и области применения.](articles/5_1_1_6_models.md)

[6+0 => 28+0]: _

7. [Сервисно - ориентированные архитектуры. Анализ интересов клиента. Выбор вариантов решений](articles/5_1_1_7_soa.md)

[4+0 => 32+0]: _

8. [Методы и средства проектирования информационных систем.](articles/5_1_1_8_methods.md)

[4+0 => 36+0]: _

9. [Case-средства для моделирования деловых процессов (бизнес-процессов).](articles/5_1_1_9_case.md)

[4+0 => 40+0]: _

[Инструментальная среда – структура, интерфейс, элементы управления.]: //TODO

[Принципы построения модели IDEF0: контекстная диаграмма, субъект моделирования, цель и точка зрения.]: ВМЕСТО_ЭТОГО_UML

[Диаграммы IDEF0: диаграммы декомпозиции, диаграммы дерева узлов, диаграммы только для экспозиции (FEO).]: ВМЕСТО_ЭТОГО_UML

[Работы (Activity). Стрелки (Arrow). Туннелирование стрелок. Нумерация работ и диаграмм. Каркас диаграммы.]: ВМЕСТО_ЭТОГО_UML

[Слияние и расщепление моделей.]: ВМЕСТО_ЭТОГО_UML

10. [Проектирование информационных систем на основе унифицированного языка моделирования UML](articles/5_1_1_10_uml.md)

[4+0 => 44+0]: ВМЕСТО_IDEF


[4+0 => 48+0]: ВМЕСТО_IDEF

11. UML. Диаграмма последовательности

[4+0 => 52+0]: ВМЕСТО_IDEF


[4+0 => 56+0]: ВМЕСТО_IDEF

11. [Особенности информационного, программного и технического обеспечения различных видов информационных систем. Экспертные системы. Системы реального времени](articles/5_1_1_11.md)

[6+0 => 62+0]: _

12. [Оценка экономической эффективности информационной системы. Стоимостная оценка проекта. Классификация типов оценок стоимости: оценка порядка величины, концептуальная оценка, предварительная оценка, окончательная оценка, контрольная оценка.](articles/5_1_1_12.md)

[8+0 => 70+0]: _

13. [Основные процессы управления проектом. Средства управления проектами](articles/5_1_1_13.md)

[4+0 => 74+0]: _

### Лабораторные

1. Практическая работа «Анализ предметной области различными методами: контент-анализ, вебометрический анализ, анализ ситуаций, моделирование и др.»
2. Практическая работа «Изучение устройств автоматизированного сбора информации»
3. Практическая работа «Оценка экономической эффективности информационной системы»
4. Практическая работа «Разработка модели архитектуры информационной системы»
Дополнительно для квалификаций " Специалист по информационным системам" и "Разработчик web и мультимедийных приложений":
5. Практическая работа «Обоснование выбора средств проектирования информационной системы»
Дополнительно для квалификаций " Специалист по информационным системам" и "Разработчик web и мультимедийных приложений": 
6. Практическая работа «Описание бизнес-процессов заданной предметной области»

## Тема 5.1.2. Система обеспечения качества информационных систем

### Лекции

1. [Основные понятия качества информационной системы. Национальный стандарт обеспечения качества автоматизированных информационных систем](articles/5_1_2_1.md)

[не дописано про госты]: _

[https://sites.google.com/site/anisimovkhv/learning/pris/lecture/tema1#p12]: _

[4+0 => 78+0]: _

2. Международная система стандартизации и сертификации качества продукции. Стандарты группы ISO.

[4+0 => 82+0]: _

3. Методы контроля качества в информационных системах. Особенности контроля в различных видах систем

[4+0 => 86+0]: _

4. Автоматизация систем управления качеством разработки.

[4+0 => 90+0]: _

5. [Обеспечение безопасности функционирования информационных систем](articles/5_1_2_5.md)

[4+0 => 94+0]: _

6. Стратегия развития бизнес-процессов. Критерии оценивания предметной области и методы определения стратегии развития бизнес-процессов. Модернизация в информационных системах

[6+0 => 100+0]: _

### Лабораторные
1. Практическая работа «Построение модели управления качеством процесса изучения модуля «Проектирование и разработка информационных систем»»
Дополнительно для квалификаций "Специалист по информационным системам" и "Разработчик web и мультимедийных приложений": 
2. Практическая работа «Реинжиниринг методом интеграции»
3. Практическая работа «Разработка требований безопасности информационной системы»
Дополнительно для квалификаций "Специалист по информационным системам" и "Разработчик web и мультимедийных приложений": 
4. Практическая работа «Реинжиниринг бизнес-процессов методом горизонтального и/или вертикального сжатия»


## Тема 5.1.3. Разработка документации информационных систем

### Лекции

1. Перечень и комплектность документов на информационные системы согласно ЕСПД и ЕСКД. Задачи документирования.

[4+0 => 104+0]: _

2. Предпроектная стадия разработки. Техническое задание на разработку: основные разделы.

[4+0 => 108+0]: _

3. Построение и оптимизация сетевого графика.

[4+0 => 112+0]: _

4. Проектная документация. Техническая документация. Отчетная документация

[6+0 => 118+0]: _

5. [Пользовательская документация.](./articles/5_1_3_5.md) Маркетинговая документация. 

[4+0 => 122+0]: _

6. Самодокументирующиеся программы. 

[4+0 => 126+0]: _

7. Назначение, виды и оформление сертификатов.

[4+0 => 130+0]: _

### Лабораторные
1. Практическая работа «Проектирование спецификации информационной системы индивидуальному заданию» 
2. Практическая работа «Разработка общего функционального описания программного средства по индивидуальному заданию»
3. Практическая работа «Разработка руководства по инсталляции программного средства по индивидуальному заданию»
4. Практическая работа «Разработка руководства пользователя программного средства по индивидуальному заданию»
5. Лабораторная работа «Изучение средств автоматизированного документирования»

# МДК. 05.02 Разработка кода ИС

## Работа с БД

1. [Знакомство с SQL](https://github.com/kolei/yotc/blob/master/articles/sql_for_beginner.md)
-->

<!--  
ERD,
импорт данных 
дописать про update, delete -->

# МДК. 05.03 Тестирование информационных систем

[46+24]: ФГОС

## Тема 5.3.1 Отладка и тестирование информационных систем

### Лекции

1. [Тестирование и тестировщики](articles/5_3_1_1_intro.md)

[6+0]: тут_ещё_вспомнаем_про_библиотеку_классов

2. [Жизненный цикл тестирования](articles/5_3_1_2_lifecycle.md)

[6(12)+0]: большой_объем

3. [Виды и методы тестирования](articles/5_3_1_3_vidy.md) (в том числе автоматизированные)

4. [Тестовые сценарии, тестовые варианты. Оформление результатов тестирования.](articles/5_3_1_4_testcase.md)

<!-- [(+12)]: _ -->

5. Инструментарии анализа качества программных продуктов в среде разработки.

6. [Обработка исключительных ситуаций. Методы и способы идентификации сбоев и ошибок.](articles/5_3_1_6_exceptions.md)

[7. Выявление ошибок системных компонентов. - по ФГОС, но не представляю что давать]: _

8. [Реинжиниринг бизнес-процессов в информационных системах.](articles/5_3_1_8_reengeniring.md)

9. [Создание библиотеки классов](articles/5_3_1_9_classlib.md)

10. [Создание UNIT-тестов](./articles/5_3_1_10_unit_test.md)

### Лабораторнo-практические работы
1. Лабораторная работа «Разработка тестового сценария проекта»
2. Лабораторная работа «Разработка тестовых пакетов»
3. Лабораторная работа «Использование инструментария анализа качества»
4. Лабораторная работа «Анализ и обеспечение обработки исключительных ситуаций»
5. Лабораторная работа «Функциональное тестирование»
6. Лабораторная работа «Тестирование безопасности»
7. Лабораторная работа «Нагрузочное тестирование, стрессовое тестирование»
8. Лабораторная работа «Тестирование интеграции»
9. Лабораторная работа «Конфигурационное тестирование»
10. Лабораторная работа «Тестирование установки»


## [Учебная практика](articles/praktika_I.md)

## [Курсовой проект](articles/kp2.md)

<!-- ПООП

Раздел 1. Технологии проектирования и дизайн информационных систем

Тема 5.1.1. Основы проектирования информационных систем

Содержание 

    1. Основные понятия и определения ИС. Жизненный цикл информационных систем

    2. Организация и методы сбора информации. Анализ предметной области. Основные понятия системного и структурного анализа.

    3. Постановка задачи обработки информации. Основные виды, алгоритмы и процедуры обработки информации, модели и методы решения задач обработки информации.

    4. Основные модели построения информационных систем, их структура, особенности и области применения.

    5. Сервисно - ориентированные архитектуры. Анализ интересов клиента. Выбор вариантов решений

    6. Методы и средства проектирования информационных систем. Case-средства для моделирования деловых процессов (бизнес-процессов). Инструментальная среда –структура, интерфейс, элементы управления.

    7. Принципы построения модели IDEF0: контекстная диаграмма, субъект моделирования, цель и точка зрения. 

    8. Диаграммы IDEF0: диаграммы декомпозиции, диаграммы дерева узлов, диаграммы только для экспозиции (FEO). 

    9. Работы (Activity). Стрелки (Arrow). Туннелирование стрелок. Нумерация работ и диаграмм. Каркас диаграммы.

    10. Слияние и расщепление моделей.

    11. Особенности информационного, программного и технического обеспечения различных видов информационных систем. Экспертные системы. Системы реального времени

    12. Оценка экономической эффективности информационной системы. Стоимостная оценка проекта. Классификация типов оценок стоимости: оценка порядка величины, концептуальная оценка, предварительная оценка, окончательная оценка, контрольная оценка.

    13. Основные процессы управления проектом. Средства управления проектами

В том числе практических занятий и лабораторных работ 

    1. Практическая работа «Анализ предметной области различными методами: контент-анализ, вебометрический анализ, анализ ситуаций, моделирование и др.»

    2. Практическая работа «Изучение устройств автоматизированного сбора информации»

    3. Практическая работа «Оценка экономической эффективности информационной системы»

    4. Практическая работа «Разработка модели архитектуры информационной системы»

    5. Практическая работа «Обоснование выбора средств проектирования информационной системы»

    6. Практическая работа «Описание бизнес-процессов заданной предметной области»

Тема 5.1.2. Система обеспечения качества информационных систем
Содержание 

    1. Основные понятия качества информационной системы. Национальный стандарт обеспечения качества автоматизированных информационных систем.

    2. Международная система стандартизации и сертификации качества продукции. Стандарты группы ISO.

    3. Методы контроля качества в информационных системах. Особенности контроля в различных видах систем

    4. Автоматизация систем управления качеством разработки.

    5. Обеспечение безопасности функционирования информационных систем

    6. Стратегия развития бизнес-процессов. Критерии оценивания предметной области и методы определения стратегии развития бизнес-процессов. Модернизация в информационных системах

В том числе практических занятий и лабораторных работ

    1. Практическая работа «Построение модели управления качеством процесса изучения модуля «Проектирование и разработка информационных систем»»

    2. Практическая работа «Реинжиниринг методом интеграции»

    3. Практическая работа «Разработка требований безопасности информационной системы»

    4. Практическая работа «Реинжиниринг бизнес-процессов методом горизонтального и/или вертикального сжатия»

Тема 5.1.3. Разработка документации информационных систем
Содержание

    1. Перечень и комплектность документов на информационные системы согласно ЕСПД и ЕСКД. Задачи документирования

    2. Предпроектная стадия разработки. Техническое задание на разработку: основные разделы. 

    3. Построение и оптимизация сетевого графика.

    4. Проектная документация. Техническая документация. Отчетная документация

    5. Пользовательская документация. Маркетинговая документация

    6. Самодокументирующиеся программы. 

    7. Назначение, виды и оформление сертификатов.

В том числе практических занятий и лабораторных работ

    1. Практическая работа «Проектирование спецификации информационной системы индивидуальному заданию» 

    2. Практическая работа «Разработка общего функционального описания программного средства по индивидуальному заданию»

    3. Практическая работа «Разработка руководства по инсталляции программного средства по индивидуальному заданию»

    4. Практическая работа «Разработка руководства пользователя программного средства по индивидуальному заданию»

    5. Лабораторная работа «Изучение средств автоматизированного документирования»


МДК. 05.03 Тестирование информационных систем
Тема 5.3.1. Отладка и тестирование информационных систем
Содержание 

    1. Организация тестирования в команде разработчиков

    2. Виды и методы тестирования (в том числе автоматизированные)

    3. Тестовые сценарии, тестовые варианты. Оформление результатов тестирования

    4. Инструментарии анализа качества программных продуктов в среде разработке. 

    5. Обработка исключительных ситуаций. Методы и способы идентификации сбоев и ошибок. 

    6. Выявление ошибок системных компонентов. 

    7. Реинжиниринг бизнес-процессов в информационных системах. 

В том числе практических занятий и лабораторных работ

    1. Лабораторная работа «Разработка тестового сценария проекта»

    2. Лабораторная работа «Разработка тестовых пакетов»

    3. Лабораторная работа «Использование инструментария анализа качества»

    4. Лабораторная работа «Анализ и обеспечение обработки исключительных ситуаций»

    5. Лабораторная работа «Функциональное тестирование»

    6. Лабораторная работа «Тестирование безопасности»

    7. Лабораторная работа «Нагрузочное тестирование, стрессовое тестирование»

    8. Лабораторная работа «Тестирование интеграции»

    9. Лабораторная работа «Конфигурационное тестирование»

    10. Лабораторная работа «Тестирование установки»

 -->