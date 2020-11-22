# Resheto_Erastofena

Описание взято с: http://py-algorithm.blogspot.com/2011/04/blog-post_09.html
РЕШЕТО́ ЭРАТОСФЕ́НА — АЛГОРИТМ НАХОЖДЕНИЯ ВСЕХ ПРОСТЫХ ЧИСЕЛ ДО НЕКОТОРОГО ЦЕЛОГО ЧИСЛА N, КОТОРЫЙ ПРИПИСЫВАЮТ ДРЕВНЕГРЕЧЕСКОМУ МАТЕМАТИКУ ЭРАТОСФЕНУ КИРЕНСКОМУ.

Для нахождения всех простых чисел не больше заданного числа n, следуя методу Эратосфена, нужно выполнить следующие шаги:
  1. Выписать подряд все целые числа от двух до n (2, 3, 4, …, n).
  2. Пусть переменная p изначально равна двум — первому простому числу.
  3. Вычеркнуть из списка все числа от 2p до n, делящиеся на p (то есть, числа 2p, 3p, 4p, …)
  4. Найти первое не вычеркнутое число, большее чем p, и присвоить значению переменной p это число.
  5. Повторять шаги 3 и 4 до тех пор, пока p не станет больше, чем n
  6. Все не вычеркнутые числа в списке — простые числа.
  
  
TODO: 1) сделать в виде функции 2) поменять имена переменных на более общие ( было написано для другого алгоритма) 3) посмотреть:http://py-algorithm.blogspot.com/2011/04/blog-post_09.html , добавить del и, возможно, другие улучшения кода
