# Задача: «Оптимизация расходов на санитарное содержание улиц»

## Направление «Умный город»

### Описание:
На данный момент существует необходимость оптимизировать работу служб санитарного поддержания улиц. Решение, созданное в рамках хакатона, призвано помочь сократить расходы на обеспечение чистоты улиц и увеличить эффективность работы ответственных служб.

### Задача:
Необходимо разработать алгоритм оптимизации распределения нагрузки и технического оснащения уборочной техники. Разработка должна быть способна:
1. Оптимизировать распределение навесного оборудования для уборки по транспортным средствам;
2. Минимизировать количеств задействованной техники и времени, затрачиваемого на выполнение технологических операций.

### Детали:

Участникам будут переданы следующие входные данные для разработки:
* Типы транспортных средств;
* Типы навесного оборудования для транспортных средств;
* Характеристики отдельно взятых предприятий, осуществляющих уборку города (уборочная площадь, наличие уборочной техники различных типов);
* Перечень технологических операций по уборке улиц и дворов (с указанием времени выполнения, подходящих для каждой операций комбинаций типов техники и оборудования).

### Решение команды КГЭУ (Автор: Мишагин Тимур):
Составление матриц на основе комбинаторного алгоритма и дальнейшее решения системы уравнений первого порядка используя метод Линейной алгебры "Симлпекс-метод".
**Подробнее смотреть файл input.txt**
