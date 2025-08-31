# Описание набора данных
### Обзор
Данные были разделены на две группы:
* обучающий набор (train.csv)
* тестовый набор (test.csv)

**Обучающий набор данных** должен использоваться для построения моделей машинного обучения. Для обучающего набора мы предоставляем результаты (также известные как «истинные данные») для каждого пассажира.

**Тестовый набор** следует использовать для проверки эффективности вашей модели на ранее неизвестных данных.
### Словарь данных
<table>
<tbody>
<tr><th><b>Переменная</b></th><th><b>Определение</b></th><th><b>Ключ</b></th></tr>
<tr>
<td>survival</td>
<td>Survival</td>
<td>0 = No, 1 = Yes</td>
</tr>
<tr>
<td>pclass</td>
<td>Ticket class</td>
<td>1 = 1st, 2 = 2nd, 3 = 3rd</td>
</tr>
<tr>
<td>sex</td>
<td>Sex</td>
<td></td>
</tr>
<tr>
<td>Age</td>
<td>Age in years</td>
<td></td>
</tr>
<tr>
<td>sibsp</td>
<td># of siblings / spouses aboard the Titanic</td>
<td></td>
</tr>
<tr>
<td>parch</td>
<td># of parents / children aboard the Titanic</td>
<td></td>
</tr>
<tr>
<td>ticket</td>
<td>Ticket number</td>
<td></td>
</tr>
<tr>
<td>fare</td>
<td>Passenger fare</td>
<td></td>
</tr>
<tr>
<td>cabin</td>
<td>Cabin number</td>
<td></td>
</tr>
<tr>
<td>embarked</td>
<td>Port of Embarkation</td>
<td>C = Cherbourg, Q = Queenstown, S = Southampton</td>
</tr>
</tbody>
</table>

### Переменные примечания
**pclass** : Прокси-фактор социально-экономического статуса (СЭС)
* 1-й = Высший
* 2-й = Средний
* 3-й = Низший

**age** : Возраст дробный, если меньше 1. Если возраст оценивается, то представлен ли он в форме xx.5

**sibsp** : Набор данных определяет семейные отношения следующим образом...
* Sibling = брат, сестра, сводный брат, сводная сестра
* Spouse = муж, жена (любовницы и женихи игнорировались)

**parch** : Набор данных определяет семейные отношения следующим образом...
* Parent = мать, отец
* Child = дочь, сын, падчерица, пасынок
* Некоторые дети путешествовали только с няней, поэтому parch=0 для них.
