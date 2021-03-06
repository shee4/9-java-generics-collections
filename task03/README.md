# Задание 03 Анаграммы

Реализуйте алгоритм поиска анаграмм в заданном словаре. 

Метод findAnagrams принимает слова, разделенные разрывом строки, в виде InputStream.

На выходе должен получиться список, состоящий из наборов слов, каждое из которых является анаграммой других слов в наборе.

- Все слова должны быть приведены в нижний регистр.
- Каждый набор должен состоять минимум из 2 слов.
- Слова в каждом наборе должны быть отсортированы в алфавитном порядке.
- Наборы в списке должны быть отсортированы по первым словам в наборах, в алфавитном порядке.

Алгоритм должен учитывать следующие возможные ошибки во входных данных:

- исключать слова, содержащие меньше 3 символов,
- исключать слова, содержащие символы, отличные от русских букв,
- учитывать повторяющиеся слова только 1 раз.

### Пример входных данных
```
трос
накал
рост
чесотка
сорт
отсечка
```

### Результат
```
[отсечка, чесотка]
[рост, сорт, трос]
```
