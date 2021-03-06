# Bureaucracy

> Чу́дище о́бло, озо́рно, огро́мно, стозе́вно и ла́яй

Here I will place information needed to fill different bureaucratic forms.
A text will be provided in Ukrainian so I can copy-paste it into Microsoft Word (which I don't have at the moment as Linux user).

<table style="width:100%">
  <tr>
    <th rowspan="2">Кредити (всього)</th>
    <th rowspan="2">загальний обсяг (год)</th>
    <th colspan="6">Аудиторних (год)</th> 
    <th rowspan="2">Самостійна робота (год)</th>
  </tr>
  <tr>
    <td>всього<br>аудиторних</td> 
    <td>лекції</td> 
    <td>практичні</td>
    <td>семінарські</td>
    <td>лабораторні</td> 
    <td>індивідуальні</td>
  </tr>
  <tr>
    <td>3</td>
    <td>90</td> 
    <td>48</td>
    <td>32</td>
    <td>-</td> 
    <td>16</td>
    <td>-</td>
    <td>-</td>
    <td>42</td>
  </tr>
</table>

## ЗМІСТОВИЙ МОДУЛЬ 1
**Інструменти машинного навчання**

### Тема 1. Місце класичних методів машинного навчання у компʼютерних науках та огляд інструментів необхідних для курсу.

#### Лекція 1. 

* "Ландшафт" машинного навчання. 
Класифікація методів машинного навчання, місце класичних методів машинного навчання у загальній картині.
* Поняття моделі. Побудова моделі. Валідація моделі. Основні проблеми, що можуть виникнути з моделями. Виявлення та боротьба з перенавчанням та недонавчаннням. Дисперсія та зміщення.
* Інструменти, що будуть використовуватися в процесі навчання: Google Colab, GitHub, CodeSculptor.
* Вступ в Python. Запуск скриптів Google Colab. Чисельні типи даних. Умови та цикли.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Неявна конвертація типів.
* Вихід з циклу за умовою, break та continue.

#### Лекція 2.

* Мова Python. Функції. Лямбда-функції. Списки та словники в Python. Тип даних string (рядок).
* Огляд обʼєктно-орієнтованого програмування. Клас та обʼєкт. Створення класів. 
* Модулі. Імпорт модулів у Python.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Генератори.
* Використання списків та словників при ітерації. Одночасна ітерація за кількома списками, zip.

### Тема 2. Необхідні допоміжні бібліотеки.

#### Лекція 3.

* Бібліотека numpy. Масиви numpy.array. Переваги та недоліки numpy.array.
* Розмірності, зрізи та підмасиви.
* Універсальні функції. Переваги та приклади застосування.
* Броадкастінг. Правила та приклади застосування.
* Маски. Складні індекси.
* Сортування масивів.


##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Композиції універсальних функцій для прискорення виконання коду.
* Порівняння роботи списків та масивів numpy.array.

#### Лекція 4.

* Бібліотека Pandas. Об’єкти Series, DataFrame та Index.
* Індексування та вибір даних. Універсальні функції.
* Робота з пропусками у даних.
* Ієрархічне індексування, мультиіндекси.
* Поєднання різних таблиць: concat, join, merge.
* Агрегація та групування. Техніка split-apply-combine.


##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Індексування таблиці за вибраним стовпчиком.
* Завантаження даних з файлу. Формат "дані, розділені комою" (csv).

#### Лекція 5.

* Бібліотека MatPlotLib для візуалізації.
* Представлення наукових даних. Види графіків. Приклади вдалої та невдалої інфографіки. Типові помилки.
* Прості графіки: line plot, scatter plot, errorbar.
* Візуалізація тривимірних даних у двох вимірах. Contour plot та density plot.
* Візуалізація тривимірних даних у трьох вимірах. 
* Гістограми та бінаризація.
* Налаштування відображень графіків. Множинні графіки.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Налаштування відображення, кольори та товщини ліній.
* Легенди графіків, різні налаштування, бібліотека стилів seaborn.

## ЗМІСТОВИЙ МОДУЛЬ 2
**Методи машинного навчання**

### Тема 3. Методи класифікації та регресії.

#### Лекція 6.

* Елементи статистики для машинного навчання.
* Генеральна сукупність та вибірка. 
* Деякі широковживані розподіли імовірностей: Бернуллі, нормальний, Пуассона, гіпергеометричний та інші.
* Статистики та естіматори.
* Оцінка максимальної правдоподібності, метод MLE.
* Статистичні моделі. Коваріація та кореляція. Квартет Анкомбе.


##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Парадокс Сімпсона.
* Вивести MLE для нормального розподілу з наперед заданим середнім.
* Вивести MLE для нормального розподілу з наперед заданимою варіацією.

#### Лекція 7.

* Наївний баєсів класифікатор.
* Теорема Баєса. Приклади застосування, парадокс Монті Холла.
* Задача класифікації. Класифікація на прикладі фільтрування спаму.
* Гаусів наївний баєсів класифікатор.
* Класифікація тексту. Мультиноміальний наївний баєсів класифікатор. Бернулів наївний баєсів класифікатор.


##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Ознаки для класифікації тексту: наявність слова, простий підрахунок слів та TFIDF (term frequency inverse document frequency).

#### Лекція 8.

* Елементи теорії математичної оптимізації.
* Типи задач оптимізації. Задачі з обмеженнями. Лагранжіан.
* Дуальна задача.
* Тестові функції. Типові "патології". Функція Розенброка та інші.
* Ітеративні методи різних порядків. Метод Нелдера-Міда. Метод градієнтного спуску та його модифікації (Nesterov Momentum, AdaGrad, RMSprop та інші). Метод Ньютона. Методи довірчих інтервалів.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Метод оптимізованого градієнтного спуску.
* Зв'язок між методом Ньютона та псевдооберненою матрицею. Типові проблеми методу.

#### Лекція 9.

* Проста лінійна регресія. Полілінійна регресія.
* Лінійна регресія як задача мінімізації. Лінійна регресія з точки зору статистики. Лінійна регресія з точки зору лінійної алгебри. Псевдообернена матриця.
* Лінійна регресія в довільному базисі. Регресія поліноміальному базисі, звʼязок з рядом Тейлора. Регресія в гаусовому базисі.
* Регуляризація. Поняття квадратично обмеженої квадратичної програми. Регуляризації Ridge та Lasso. Регуляризація Elastic Net.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Коефіцієнт детермінації. Нормований коефіцієнт детермінації.
* Регресія в базисі тригонометричних функції. Зв'язок з рокладом Фур'є.

#### Лекція 10.

* Машини опорних векторів.
* Постановка задачі в термінах лінійно-роздільної вибірки. Поняття опорного вектора. Машина опорних векторів як задача оптимізації.
* Лінійно-нероздільні вибірки. Пом'якшення границь. Контроль "проникності границі".
* Дуальна задача для машини опорних векторів. Ядровий метод. Найбільш часто вживані ядра, ядро радіальних базисних функцій.
* Різноманітні модифікації машини опорних векторів. Регресія за допомогою машини опорних векторів.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Параметр гамма ядра радіальних базисних функцій. Його значення та вплив на класифікацію.
* Алгоритм послідовної мінімальної оптимізації (Sequential minimal optimization, SMO) для навчання машини опорних векторів.

#### Лекція 11.

* Дерева ухвалення рішень та випадковий ліс.
* Поняття про логічні методи класифікації. Оцінка зміни кількості інформації після класифікації вибірки предикатом. Помилка класифікації, ентропія та індекс Джині.
* Побудова дерева рішень. Порівняння методів оцінки ефективності вузлів.
* Ансамблі естіматорів. Ансамбль естіматорів, що голосують. Поняття про випадковий ліс.
* Нестійкість дерева ухвалення рішень, поняття про бустінг, AdaBoost.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Регресія за допомогою випадкового лісу.
* Методи обрізання дерева рішень (pruning).

### Тема 4. Методи кластеризації та пониження розмірності.

#### Лекція 12.

* Метод головних компонент.
* Звʼязок між варіацією проекції ознак та методом головних компонент. Метод головних компонент як задача оптимізації.
* Метод головних компонент з точки зору лінійної алгебри. Власний розклад матриці. Сингулярний розклад матриці. Приклад сингулярного розкладу.
* Метод головних компонент для пониження розмірності та візуалізації. Приклад звʼязаних маятників.
* Метод головних компонент для фільтрування шуму. Приклад фільтрування шуму.


##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Метод головних компонент та нормальні моди зв'язаних осциляторів.
* Пониження розмірності графічної інформації, eigenfaces.

#### Лекція 13.

* Метод k-середніх.
* Кластеризація. Часто вживані тестові набори даних для кластеризації.
* Метод k-середніх. Алгоритми Ллойда, мак Квіна, Хартігана-Вонга. Метод k-середніх з точки зору діаграм Вороного.
* Оцінка кількості кластерів. Метод плеча. Аналіз силуетів.
* Проблема локальних мінімумів у методі k-середніх.
* Приклади застосування: розпізнавання рукописних цифр, квантизація кольорів.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Модифікації методу k-середніх: Mini Batch, k-медіани, PAM-алгоритм, метод k-середніх++, нечітка кластеризація.


#### Лекція 14.

* Модель суміші гаусіан.
* Кластеризація та модель суміші. Пряма задача. Обернена задача. Поняття генеративної моделі.
* Модель суміші гаусіан з точки зору максимальної правдоподібності.
* Підхід максимізації математично сподівання, ЕМ-алгоритм.
* Метод к-середніх з точки зору моделі суміші гаусіан.
* Модель суміші гаусіан для оцінки густини.
* Приклад генеративної моделі на базі суміші гаусіан.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Модель суміші гаусіан з точки зору оцінки максимальної правдоподібності (Maximum Likelihood Estimation).
* ЕМ-алгоритм для методу k-середніх.


#### Лекція 15.

* Ядрова оцінка густини розподілу.
* Гістограми. Проблема вибору розмірів комірок (бінів).
* Мотивація виникнення ядрова оцінки густини розподілу. Часто вживані ядра.
* Вибір розміру ядра: правило Сільвермана, алгоритм Шітера-Джонса та перехресна валідація.
* Ядрова оцінка густини розподілу як модель суміші.
* Приклади застосування.


##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Ядрова оцінка густини розподілу як ненаївний Баєс.
* Застосування ядрової оцінки густини розподілу для ілюстрації.

#### Лекція 16.

* Куди рухатись далі: нейромережі та інші алгоритми машинного навчання.
* Поняття про нейромережу. Нейромережа з функціональної точки зору.
* Приклади застосування нейромереж на практиці. Їх можливості.
* Поняття про згортку. Згорткова нейромережа (CNN).
* Архітектури кількох популярних нейромереж.

##### Завдання для самостійної роботи (<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Belgian_road_sign_A51.svg/200px-Belgian_road_sign_A51.svg.png" width="20px"/> год.)
1. Вивчення матеріалу лекції.
2. Опрацювання матеріалу, що винесений на самостійне вивчення:
* Загальний огляд існуючих популярних засобів розробки та тренування нейромереж.
