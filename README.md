getIn
Реализуйте функцию getIn, которая извлекает из массива (который может быть любой глубины вложенности) значение по указанным ключам. 

union(...$arrays)
Реализуйте функцию union(...$arrays), которая находит объединение всех переданных массивов. Функция принимает на вход от одного массива и больше. Ключи исходных массивов не сохраняются (т.е. все значения итогового массива заново индексируются: 0, 1, 2, ...).

getGirlFriends
Реализуйте функцию getGirlFriends, которая принимает на вход список пользователей и возвращает плоский список подруг всех пользователей (без сохранения ключей). Друзья каждого пользователя хранятся в виде массива в ключе friends. Пол доступен по ключу gender и может принимать значения male или female.

countWords
Реализуйте функцию countWords(), которая считает количество слов в предложении и возвращает ассоциативный массив в котором ключи это слова (приведенные к нижнему регистру), а значения — это то сколько раз слово встретилось в предложении. Слова в предложении могут находиться в разных регистрах. Перед подсчетом их нужно приводить в нижний регистр, чтобы не пропускались дубли.

getChunked
Реализуйте функцию getChunked, которая принимает на вход массив и число, задающее размер чанка (куска). Функция должна вернуть массив, состоящий из чанков указанной размерности.

fib
Реализуйте функцию fib(), находящую положительные числа Фибоначчи. Аргументом функции является порядковый номер числа.

getTheNearestLocation
Реализуйте функцию getTheNearestLocation(), которая находит место ближайшее к указанной точке на карте и возвращает его. Параметры функции:
$locations – массив мест на карте. Каждое место это массив из двух элементов, где первый элемент это название места, второй – точка на карте (массив из двух чисел x и y).
$point – текущая точка на карте. Массив из двух элементов-координат x и y.
