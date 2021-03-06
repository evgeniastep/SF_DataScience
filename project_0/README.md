# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)   
[3. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[4. Результат](.README.md#Результат)    
[5. Выводы](.README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](_)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python


### Этапы работы над проектом  
Выполнена функция random_predict, которая работает в 3 этапа:
- Генерирует рандомное число в интервале от 1 до 100
- Высчитывает частное между загаданным и предсказанным рандомным числом.
- Если часное больше 1, то умножает предсказанное число на частное
Выполнена функция score_game, которая высчитывает за какое количство попыток в среднем за 1000 подходов угадывает наш алгоритм


:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
Алгорим угадывает число в среднем за 6 попыток

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
Если добавить уменьшение и увеличение предсказываемого числа на 1, при сравнении number < predict_number или number > predict_number соответственно. Алгорим в среднем будет угадывать число за 4 попытки.


:arrow_up:[к оглавлению](.README.md#Оглавление)

