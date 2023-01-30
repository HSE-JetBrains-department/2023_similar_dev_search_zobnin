# Исходный код как данные

### Зобнин Алексей, БПИ202

## Описание задачи:
Поиск схожих разработчиков путём анализа кода в их репозиториях: сравнение по используемым языкам программирования, фреймворкам, устройству кода (на основе AST кода), именований в коде.

## Этапы работы над проектом:

1. Поиск подходящих репозиториев в GitHub.
2. Клонирование репозиториев на рабочее устройство.
3. Достать всю необходимую информацию из системы контроля версий.
4. Разметить (классифицировать) репозитории по языкам программирования и фреймворкам.
5. Отфильтровать репозитории и часть кода в них.
6. Распарсить исходный код, извлечь из AST необходимую информацию - имена переменных, импорты и тд.
7. По полученным представлениям найти наиболее похожих друг на друга разработчиков.
