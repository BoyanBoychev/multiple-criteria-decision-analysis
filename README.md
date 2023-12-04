﻿# Multiple Criteria Decision Analysis

## Todo:

* Да се теста AHP метода.
* Да се разгледа и тества Topsis Pairwise метода дали работи правилно.
* Да се допълни weighted_sum unit test-a.
* Да се добави Promethee Unit Test
* Да се допълни Promethee (return value, more preference functions)


## Done 

* Добавен е метода AHP (както се разбрахме без sub criteria) и unit tests към него.
* Добавен е метода SMART и unit tests към него.
* Добавен е метода Promethee
* Добавен е Pairwise метод за намиране на тегла.


## Return Values of All Methods

* Всички методи трябва да връщат една и съща стойност. В момента методите връщат подреден в нисходящ ред списък от речници, в които има ключове "name" и "score". Списъкът е подреден по ключа "score".
  * Пример: [{"name": "BMW", "score": 0.95}, {"name": "Audi", "score": 0.7}, {"name": "Mercedes", "score": 0.56}]

