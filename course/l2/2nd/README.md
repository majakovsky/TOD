# Лабораторная работа №2.2

### *Задания для выполнения :*

4.1 Посчитайте количество рецептов, представленных каждым из участников (contributor_id). Какой участник добавил максимальное кол-во рецептов?

4.2 Посчитайте средний рейтинг к каждому из рецептов. Для скольких рецептов отсутсвуют отзывы?

4.3 Посчитайте количество рецептов с разбивкой по годам создания.

5.1 При помощи объединения таблиц, создайте DataFrame, состоящий из четырех столбцов: id, name, user_id, rating. Рецепты без отзывов должны отсутствовать в данной таблице. Подтвердите правильность работы вашего кода, выбрав рецепт, не имеющий отзывов, и выведя на экран строку из полученного DataFrame, содержащую информацию об этом отзыве.

5.2 При помощи объединения таблиц и группировок, создайте DataFrame, состоящий из трех столбцов: recipe_id, name, review_count. У рецептов, для которых отсутствуют отзывы, в соответствущем столбце должен быть указан 0. Подтвердите правильность работы вашего кода, выбрав рецепт, не имеющий отзывов, и выведя на экран строку из полученного DataFrame, содержащую информацию об этом отзыве.

5.3. Выясните, отзывы, добавленные в каком году, имеют наименьший средний рейтинг?

6.1 Отсортируйте таблицу в порядке убывания величины столбца name_word_count и сохраните результаты выполнения заданий 3.1-3.3 в csv файл.

6.2 Воспользовавшись pd.ExcelWriter, cохраните результаты 5.1 и 5.2 в файл: на лист с названием Рецепты с оценками сохраните результаты выполнения 5.1; на лист с названием Количество отзывов по рецептам сохраните результаты выполнения 5.2.