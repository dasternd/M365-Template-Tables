# M365-Template-Tables
Шаблон таблиц для заполнения первичных данных школы для настройки окружения в Microsoft 365.

## Таблица Классы
Таблица **Классы** представлена в виде матрицы, где в столбце под каждым классом укажите литеру параллели класса. Если в школе 5 первых классов, то в столбце **1 класс** измените в ячейках **А**, **Б**, **В**, **Г**, **Д**, **Е** значение на **Да**. Укажите параллели с 1 по 11 классы.

![](https://github.com/dasternd/M365-Template-Tables/blob/main/table_classes.png)

## Таблица Предметы
Таблица **Предметы** также представлена в виде матрицы, в столбце под каждым классом отметьте наличие проводимого предмета. Например, в 5 классе изучают предмет Краеведения, таким образом на пересечении столбца **5 класс** и строки предмета **Краеведение** выберите значение **Да**. Отметьте с 1 по 11 класс предметы изучающие в классах.

Если в списке не нашли предмет, который изучают в школе, выберите строку с предметом, который отсутствует в школе и замените на название отсутствующего предмета. Укажите наличие (Да) или отсутствие (Нет) предметов с 1 по 11 классы.

![](https://github.com/dasternd/M365-Template-Tables/blob/main/table_subjects.png)

## Таблица Учителя
Таблицу **Учителя** заполните либо вручную, либо выгрузить информацию из учетной системы сотрудников, которая используется в школе и скопируйте в таблицу.

![](https://github.com/dasternd/M365-Template-Tables/blob/main/table_teachers_data.png)

Поля **Фамилия**, **Имя**, **Отчество**, **Должность** обязательные. Поля **Предмет**, **Класс** и **Класс2** заполняются при необходимости.

В поле Должность укажите должность соответствующая сотруднику: **Директор**, **Завуч**, **Учитель**.

В поле **Предмет** укажите основной предмет, который преподает сотрудник. Например, сотрудник преподает урок физики, тогда в поле в родительском падеже укажите "физики" (учитель чего?).

В поле **Класс** укажите название класса, например, "7Б", если учитель работает классным руководителем у этого класса.

Поле **Класс2** заполните по такому же принципу, если у учителя второй класс руководства. Как правило два класса указывают для учителей начальных классов.

## Таблица Ученики
Таблица **Ученики** содержит сотни записей. Если невозможно подготовить список автоматизированным путем, поручите собрать информацию классным руководителям. Полученную информацию объедините в одну таблицу.

![](https://github.com/dasternd/M365-Template-Tables/blob/main/table_students_data.png)
