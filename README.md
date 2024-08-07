Тестирование формы для оформления паспортов РФ

1. Техника граничных значений

Граничные значения:

1. Минимально допустимое значение:
- Входное значение: 0
- Ожидаемый результат: “Нельзя оформить” (в соответствии с законодательством).
2. Максимально допустимое значение: 115
- Входное значение: 115
- Ожидаемый результат: “Можно оформить” (в соответствии с законодательством).
3. Значение, меньше минимального: -1
- Входное значение: -1
- Ожидаемый результат: “Ошибка” (выход за пределы диапазона).
4. Значение, больше максимального: 116
- Входное значение: 116
- Ожидаемый результат: “Ошибка” (выход за пределы диапазона).
5. Значение на границе между допустимыми и недопустимыми:
- Входное значение: 1 (для минимального допустимого значения).
- Ожидаемый результат: “Можно оформить” (если условие оформляется).
- Входное значение: 114 (для значений до максимально допустимого).
- Ожидаемый результат: “Можно оформить” (если условие оформляется).



2. Техника классов эквивалентности

Классы эквивалентности:

1. Корректные значения (в пределах диапазона):
Примеры: 
- Входное значение: 25 (в возрасте для паспорта)
- Ожидаемый результат: “Можно оформить”
- Входное значение: 100 (в возрасте для паспорта)
- Ожидаемый результат: “Можно оформить”
2. Недопустимые значения (меньше минимального):
Примеры: 
- Входное значение: -5
- Ожидаемый результат: “Ошибка”
3. Недопустимые значения (больше максимального): 
Примеры:
- Входное значение: 130
- Ожидаемый результат: “Ошибка”
4. Граничные значения (0 и 115):
Примеры:
- Входное значение: 0
- Ожидаемый результат: “Нельзя оформить”
- Входное значение: 115
- Ожидаемый результат: “Можно оформить”
