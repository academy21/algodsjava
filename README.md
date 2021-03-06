# Алгоритмы и структуры данных на Java

Проект по алгоритмам и структурам данных на языке программирования Java студентов первого курса ШЕН ДВФУ специальности Прикладная математика и информатика. 

# Цель проекта

Проект направлен на практическое освоение алгоритмов и структур данных через их реализацию на языке программирования Python и создания на этой основе отрытого обучающего веб-ресурса, содержащего справочную информацию и демонстрацию работы реализованных алгоритмов и структур данных.

Разработку этого обучающего ресурса планируется вести максимально приближенно к реальной разработке продуктов:
- командная работа с использованием системы контроля версий git и портала Github
- совместное обсуждение задач и разработка проекта по методологии agile
- следование лучшим практикам проектирования и написания кода
- написание тестов для создаваемого функционала и использование автотестирования
- документирование создаваемого кода

# Структура проекта

Проект будет состоять из библиотеки структур данных и алгоритмов, реализованными студентами (с тестами и документацией), а также из веб-сервиса по вызову этих алгоритмов, демонстрации их работы, описанием, примерами использования и т.д. То есть помимо самой реализации алгоритмов, из открытых источников будет собран и переработан справочный обучающий материал по каждому алгоритму и структуре данных. Интерфейсом к веб-сервису будет служить веб-приложение или телеграм-бот. Конкретная архитектура всех частей проекта будет прорабатываться совместно со студентами в команде с учётом всех современных технологий и лучших практик.

# План минимум и максимум по алгоритмам и структурам данных

Поскольку практика проводится в рамках теоретического курса, покрывающего определённые темы, то план минимум будет перечислен ниже, в соответствии с теоретическим курсом.

Однако, чтобы получить более цельное представление об алгоритмах и структурах данных, а также распределить работу по студентам, по плану максимум будет реализация большинстрва [структур данных из списка википедии](https://en.wikipedia.org/wiki/List_of_data_structures), а также большинства [алгоритмов из списка википедии](https://en.wikipedia.org/wiki/List_of_algorithms), с использованием этих структур. При этом приоритет будет отдаваться алгоритмам и структурам данных, которые присутствуют в плане минимум.

## Сортировки	
- [Пузырьком](https://en.wikipedia.org/wiki/Bubble_sort)
- [Выбором](https://en.wikipedia.org/wiki/Selection_sort)
- [Вставками](https://en.wikipedia.org/wiki/Insertion_sort)
- [Подсчётом](https://en.wikipedia.org/wiki/Counting_sort)
- [Поразрядная](https://en.wikipedia.org/wiki/Radix_sort)
- [Карманная](https://en.wikipedia.org/wiki/Bucket_sort)
- [Быстрая](https://en.wikipedia.org/wiki/Quicksort)
- [Слиянием](https://en.wikipedia.org/wiki/Merge_sort)
- [Пирамидальная сортировка](https://en.wikipedia.org/wiki/Heapsort)

## Деревья	
- [Двоичная куча](https://en.wikipedia.org/wiki/Binary_heap)
- [AVL-дерево](https://en.wikipedia.org/wiki/AVL_tree)
- [Б-деревья](https://en.wikipedia.org/wiki/B-tree)
- [Очередь с приоритетом](https://en.wikipedia.org/wiki/Priority_queue)

## [Графы](https://en.wikipedia.org/wiki/Graph_theory)
- [Алгоритм Крускала](https://en.wikipedia.org/wiki/Kruskal%27s_algorithm)
- [Алдгоритм Прима](https://en.wikipedia.org/wiki/Prim%27s_algorithm)
- [Алгоритм Форда-Беллмана](https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm)
- [Алгоритм Дейкстры](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
- [Алгоритм Флойда-Уоршелла](https://en.wikipedia.org/wiki/Floyd%E2%80%93Warshall_algorithm)
- [Задача коммивояжера](https://en.wikipedia.org/wiki/Travelling_salesman_problem)
- [Задача о выборе заявок](https://ru.wikipedia.org/wiki/%D0%96%D0%B0%D0%B4%D0%BD%D1%8B%D0%B9_%D0%B0%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC)

## Поиск подстрок	
- [Алгоритм Бойера-Мура](https://en.wikipedia.org/wiki/Boyer%E2%80%93Moore_string-search_algorithm)
- [Алгоритм Кнута-Морриса-Пратта](https://en.wikipedia.org/wiki/Knuth%E2%80%93Morris%E2%80%93Pratt_algorithm)
- [Алгоритм Рабина-Карпа](https://en.wikipedia.org/wiki/Rabin%E2%80%93Karp_algorithm)

## [Хеш-таблицы](https://en.wikipedia.org/wiki/Hash_table)
- С прямой адресацией	
- С помощью цепочек	
- Хэш функции	
- Открытая адресация	
- Идеальное хэширование	

## Алгоритмы сжатия
- [Алгоритм Хаффмана](https://en.wikipedia.org/wiki/Huffman_coding)
	
## [Конечные автоматы](https://en.wikipedia.org/wiki/Finite-state_machine)

## Всё остальное
- Размещения. Генерация размещения с повторениями, без повторениями. Перестановки
- Сочетания. Представление подмножеств как целых чисел. Перебор подмножеств
- Поиск с возвратом, перебор с отсечениями
- Расписание работы конвейера. Структура оптимальной сборки, оптимальность подзадач. Рекурсивное решение. Мемоизация. Восстановление ответа
- Метод точного среднего (Амортизационный анализ)
- Поиск в глубину и его свойства, классификация ребер. Лемма о белом пути
- Поиск в ширину. Поиск кратчайшего пути на невзвешенном графе.
- ДП в пространстве ответа. Задача о рюкзаке
- Лес непересекающихся множеств.
- Кратчайшие пути из одной вершины, свойства. Отрицательные циклы
- Проверка графа на ацикличность. Подсчет компонент связности
- Задача о выборке заявок
- Непрерывная задача о рюкзаке



