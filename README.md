# Calculator
Проект калькулятора комплексных чисел на языке Python с применения архитектурных паттернов, принципов SOLID и паттернов проектирования с использованием объектно-ориентированного подхода.

В качестве логирования используется модуль logging из стандартной библиотеки Python.

Для запуска проекта
Как запустить приложение:

Убедитесь, что у вас установлен Python (версия 3.x). Для этого можно посетить официальный сайт Python (https://www.python.org/) и загрузить последнюю версию для вашей операционной системы.
Откройте командную строку или терминал и перейдите в директорию проекта complex_calculator.
Запустите приложение, выполнив команду:python main.py
Приложение попросит вас ввести два комплексных числа (действительную и мнимую части). Введите их значения и программа выдаст результат сложения, умножения и деления этих чисел.

logging_utils.py: В в этом файле определим настройки для логирования и функции для создания и использования логгера.

calculator.py: Здесь реализуем класс для калькулятора комплексных чисел, применяя SOLID-принципы, в частности, Single Responsibility Principle (SRP) и Dependency Inversion Principle (DIP).

main.py: В главном файле создадим интерфейс пользователя и основную логику приложения.
