# Полиномы

Выполнил: Галочкин Борис

Раскладка по директориям:

  - `application` содержит реализацию консольного приложения, используещего
    класс.
  - `include` содержит публичные заголовочные файлы, предназначенные для
    включения в пользовательские проекты.
  - `src` содержит реализацию классов полиномов и мономов.
  - `test` содержит модульные тесты для классов.

Руководство:

 - Инициализация через строки, каждый моном отделяется пробелами
 - Отрицательные степени пишутся без скобок
 - Умножение в мономе писать не нужно, все идущее подряд символы считаются умножением (xx ~ x^2)
 - Любые степени нужно писать через '^' символ (false: 2x2 ~ 4x; true: 2x^2 ~ 2x^2)
