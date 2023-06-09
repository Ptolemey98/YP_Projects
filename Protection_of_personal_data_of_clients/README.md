# Защитить данные клиентов страховой компании «Хоть потоп»

## Задача: <br> 
Защитить данные клиентов страховой компании «Хоть потоп». Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обосновать корректность его работы.
## Цель:<br>
Защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.

## Стек технологий:
`Pandas`
`numpy`
`sklearn`
`машинное обучение`

## Краткое описание проведённой работы:
<i> Для защиты данных клиентов страховой компании разработаны методы преобразования данных, чтобы по ним было сложно восстановить персональную информацию. 
Была проведена предобработка данных. Произведена проверка работы алгоритма модели линейной регрессии при перемножении на обратимую матрицу. Произведена проверка влияния перемножения на обратимую матрицу, а затем перемножения на обратную матрицу обратимой. Произведена проверка метрики `R2` Линейной регрессии на идентичных данных - сначала исходных, затем умноженных на обратимую матрицу, размер которой равен числу признаков. Метрики полностью совпали. Можно сделать вывод, что алгоритм работает.</i>

## Данные и выводы
<i>В результате нашей работы был разработан алгоритм, где данные были преобразованы методом умножения признаков исходных данных на обратимую матрицу. Результатом такого преобразования явилась новая (изменённая) матрица признаков, которая справилась с основными задачами по шифровке данных и при сравнении качества предсказаний с моделью из `Scikit−learn`, сохранила значения `R2` неизменными.</i>

---

#### Если проект не открывается, его можно просмотреть по ссылке: <a href='https://nbviewer.org/github/Ptolemey98/YP_Projects/blob/main/Protection_of_personal_data_of_clients/Protection_of_personal_data_of_clients_3_1.ipynb'>Protection_of_personal_data_of_clients</a>

