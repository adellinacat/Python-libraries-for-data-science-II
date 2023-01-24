# Python-libraries-for-data-science-II
Библиотеки Python для Data Science: продолжение

Урок 1. Введение в задачу классификации. Постановка задачи и подготовка данных.

Приведите по 2 примера, когда лучше максимизировать Precision, а когда Recall.

1) Если кредитная политика банка направлена на большую выручку, имеет смысл максимизировать Recall.
2) Если кредитная политика банка направлена на репутацию (большинство клиентов крупные заемщики, платежеспособные), имеет смысл максимизировать Precision.
3) В медицине при принятии решения о применении потенциально опасных препаратов, принимая во внимание необходимость их назначения и риски побочных эффектов, исходя из максимизации Recall.
4) Оценка на сейсмоактивность подразумевает увеличение Precision, когда место причисляется к сейсмоактивным.


Почему мы используем F-меру, почему, например, нельзя просто взять среднее от Precision и Recall?

1) F-мера позволяет оценить в комплексе как Precision, так и Recall.
2) F-мера позволяет увеличивать/уменьшать влияние Precision и Recall.
