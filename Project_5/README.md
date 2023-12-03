# Проект 5. Задача регрессии.

## Оглавление

[1. Описание проекта](.README.md#Описание-проекта)
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)
[5. Результат](.README.md#Результат)
[6. Выводы](.README.md#Выводы)

### Описание проекта

Учебный проект направленный на отработку и закрепление полученных знаний в рамках изучения модуля Mashing Learning - обучение с учителем, задачи регрессии. Построить несколько моделей машинного обучения используя разные алгоритмы: линейные модели, "Древесные" модели, Ансамблевые методы.

⬆️[к оглавлению](_)

### Какой кейс решаем?

Одна из компаний - агрегаторов услуг такси в Нью-Йорке обратилась с задачей автоматизации бизнес процесса и построения модели машинного обучения по предсказанию общей продолжительности поездки такси в Нью-Йорке и пригороде:

* "Клиенты заказывают такси из одной точки Нью-Йорка в другую, причем не обязательно конечная точка должна находиться в пределах города. Сколько клиент должен будет за нее заплатить? Известно, что стоимость такси в США  рассчитывается на основе фиксированной ставки + тарифная стоимость, величина которой зависит от времени и расстояния. Тарифы варьируются в зависимости от города. В свою очередь время поездки зависит от множества факторов таких как, откуда и куда клиент едет, в какое время суток совершается поездка, погодных условий и так далее."

Таким образом, необходимо разработать алгоритм, способный определять длительность поездки, который сможет прогнозировать ее стоимость самым тривиальным образом, умножая стоимость на заданный тариф.
Сервисы такси хранят огромные объёмы информации о поездках, включая такие данные как конечная, начальная точка маршрута, дата поездки и ее длительность. Эти данные можно использовать для того, чтобы прогнозировать длительность поездки в автоматическом режиме с привлечением искусственного интеллекта.

#### Цель проекта:

**Бизнес-цель**: определить характеристики и с их помощью спрогнозировать длительность поездки на такси.

**Техническая цель**: построить модель машинного обучения, которая на основе предложенных характеристик клиента будет предсказывать числовой признак — время поездки такси, то есть решить задачу регрессии.

#### Задачи проекта:

1. **Сформировать набор данных** на основе нескольких источников информации;
2. **Спроектировать новые признаки** с помощью Feature Engineering и выявить наиболее значимые при построении модели;
3. **Исследовать предоставленные данные** и выявить закономерности;
4. **Построить несколько моделей** и выбрать из них наилучшую по заданной метрике;
5. **Спроектировать процесс предсказания** времени длительности поездки для новых данных.
6. **Загрузить свое решение на платформу Kaggle** и сравнить полученные результаты с лидерами в Data Science соревновании.

**Метрика качества**

* Решение оформляется в Jupyter Notebook c соблюдением стандарта PEP-8, комментированием кода;
* Код на ***Python*** **должны быть читаемыми.** *Выводы по каждому этапу оформляются в формате ** ***Markdown* в отдельной ячейке*****;
* Структура Jupiter Notebook должна содержать, но не ограничеваться: загрузка и очистка данных, подготовка данных в рамках EDA (разведывательный анализ данных), построение нескольких моделей с применением алгоритмов: LinearRegression + PolinomialFutures, Ridge, DescisionTreeRegressor, RandomForestRegressor, GradientBoostingRegressor. Проверка эффективности предлагаемых моделей, используя метрику RMSLE;
* Загрузить предсказание на площадку Kaggle, оценить полученные результаты с участниками;
* Разместить материалы на GitHub (GitLab).

**Что практикуем**

Во время выполнения проекта отрабатываем навыки работы с несколькими источниками данных, генерации признаков, разведывательного анализа и визуализации данных, отбора признаков и построения моделей машинного обучения.

### Краткая информация о данных

При работе над данным проектом использовались данные c соревнования на Kaggle.

⬆️[к оглавлению](.README.md#Оглавление)

### Этапы работы над проектом

....

⬆️[к оглавлению](.README.md#Оглавление)

### Результаты:

* Подготовлен Jupyter Notebook - Project-5_Regression_study_format.ipynb.

⬆️[к оглавлению](.README.md#Оглавление)

### Выводы:

....

⬆️[к оглавлению](.README.md#Оглавление)

Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль
⭐️⭐️⭐️⭐️⭐️