# Лабораторная работа №2.1

Базовые операции с DataFrame:

1.1 В файлах recipes_short.csv и reviews_short.csv находится информация об рецептах блюд и отзывах на эти рецепты соответственно. Загрузите данные из файлов в виде pd.DataFrame с названиями recipes и reviews. Обратите внимание на корректное считывание столбца(ов) с индексами.

1.2 Для каждой из таблиц выведите основные параметры: * количество точек данных (строк); * количество столбцов; * тип данных каждого столбца.

1.3 Исследуйте, в каких столбцах таблиц содержатся пропуски. Посчитайте долю строк, содержащих пропуски, в отношении к общему количеству строк.

1.4 Рассчитайте среднее значение для каждого из числовых столбцов (где это имеет смысл).

1.5 Создайте серию из 10 случайных названий рецептов.

1.6 Измените индекс в таблице reviews, пронумеровав строки, начиная с нуля.

1.7 Выведите информацию о рецептах, время выполнения которых не больше 20 минут и кол-во ингредиентов в которых не больше 5.


Работа с датами в pandas:

2.1 Преобразуйте столбец submitted из таблицы recipes в формат времени. Модифицируйте решение задачи 1.1 так, чтобы считать столбец сразу в нужном формате.

2.2 Выведите информацию о рецептах, добавленных в датасет не позже 2010 года.

Работа со строковыми данными в pandas
3.1 Добавьте в таблицу recipes столбец description_length, в котором хранится длина описания рецепта из столбца description.

3.2 Измените название каждого рецепта в таблице recipes таким образом, чтобы каждое слово в названии начиналось с прописной буквы.

3.3 Добавьте в таблицу recipes столбец name_word_count, в котором хранится количество слов из названии рецепты (считайте, что слова в названии разделяются только пробелами).
