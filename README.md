# ya_professional_2020
Привожу свое решение задач отборочного тура олимпиады "Я профессионал" 2020/2021 по машинному обучению. В сумме я набрал 87 очков и прошел в полуфинал (проходным стал балл в 46 очков).

## Задача 1
Задача стояла следующая: по имеющимся данным о нефтяных месторождениях (подробнее описаны в ноутбуке) необходимо определить, является ли месторождение глубоководным или прибрежным (еще была ловушечка: несколько были размечены как "глубоководное/прибрежное", поэтому решение задачи бинарной классификации не проходило). Решил мощным и агрессивным XGBoost.

## Задача 2
В химической лаборатории растеряли данные о температуре плавления некоторых веществ. Но остались все-таки данные о температурах плавления некоторых других веществ. Используя таблицу с огромным количеством числовых признаков и (опционально, обошлось без нее) таблицу со сложно записанным составом (formula.csv) надо обучить модель, которая бы эту температуру предсказывала. Победил градиентным бустингом, просто отбросив избыточные данные.
