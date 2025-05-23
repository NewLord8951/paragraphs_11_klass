# 11-13
Параграф 13.

1.Полеимеет несколько значений:
1)	Безлесная равнина, пространство.Например, ледовое поле (переносное значение — сплошное пространство льда).
2)	Обрабатываемая под посев земля, участок земли.Например, ржаное поле.
3)	Большая ровная площадка, пространство, специально оборудованное, предназначенное для чего-либо. Например, футбольное, хоккейное поле, лётное поле.
4)	Работа, исследовательская деятельность в природных, естественных условиях.Например, геологи летом работают в поле.
5)	Пространство, в пределах которого проявляется действие каких-либо сил. Например, магнитное поле, силовое поле, поле тяготения.
6)	Область деятельности, поприще. Например, обширное поле деятельности.
7)	Основной цвет, фон под узором.Например, жёлтые цветы по голубому полю.
8)	Чистая полоса вдоль края листа в книге, тетради, рукописи.Например, тетрадь с полями, заметки на полях.
Записьимеет следующие значения:
1)	Действие по глаголу «записать»; процесс сохранения информации (как правило, текстовой) на бумаге или другом вещественном носителе.
2)	То, что записаногде-либо; информация, сохранённая на бумаге или другом носителе.Например, записи лекции, тетрадь с записями.
3)	Документ о какой-либо сделке, акт(специальное значение). Например, дарственная запись.

2.Каждому полю присваивают свой тип, чтобыорганизовать работу с базой данных и упростить её использование.

3.Некоторые типы данных, которые поддерживаются в современных СУБД:
•	Числовые.Используются для хранения чисел и позволяют производить с ними арифметические операции, сравнения и другие математические расчёты.
•	Строковые.Например, VARCHAR нужен, когда длина текста в колонке может сильно меняться, а TEXT используется для хранения длинных текстов, у которых нет ограничения по длине.
•	Дата и время.Например, DATETIME — комбинация времени и даты, DATE — дата, TIME — время, TIMESTAMP — отметка времени.
•	Логические.Принимают значения «истина» или «ложь».
•	Двоичные.Предназначены для хранения графических объектов, аудио- и видеоинформации, пространственной, хронологической и другой специальной информации.
•	Гиперссылки.Предназначены для хранения ссылок на различные ресурсы (узлы, файлы, документы и т. д.), находящиеся вне базы данных.

4.Ключи в таблице базы данных— это специальные поля или наборы полей, которые помогают идентифицировать и устанавливать связи между записями в разных таблицах. Они обеспечивают уникальность, поддерживают целостность данных и позволяют выполнять эффективные запросы и манипуляции с данными.

5.Простой ключ— это уникальный идентификатор, который включает в себя всего одно поле (атрибут).Например, в базе «Паспорта граждан страны» номер паспорта будет простым ключом: ведь не бывает двух паспортов с одинаковым номером.
Составной ключ— это идентификатор, состоящий из нескольких (два и более) атрибутов.Например, в той же базе «Паспорта граждан страны» может быть составной ключ со следующими атрибутами: фамилия, имя, отчество, дата рождения.

6.Ключ в реляционной базе данных — это столбец или набор столбцов, который идентифицирует каждую строку таблицы. Он содержит уникальные значения, дубликаты не допускаются.
Первичный ключ— это поле (или набор полей), значение которого однозначно определяет запись в таблице.Он гарантирует, что нет двух записей с одинаковым значением ключа.

7.Номер читательского билета может быть ключом таблицы, а фамилия и имя— нет, так как содержат повторяющиеся значения (например, однофамильцы) и не гарантируют уникальность записи.

8.Один и те же данные в одной ситуации могут быть ключом, а в другой нет, если в зависимости от контекста они обеспечивают уникальность в разных ситуациях.
Естественный ключ обеспечивает уникальность из самой сущности предметной области. Например, в таблице «Работник» поле «Табельный номер» может быть естественным ключом, так как не может быть двух работников с одинаковым табельным номером.
Искусственный ключ вводится дополнительно для обеспечения уникальных значений. Чаще всего это поле типа счётчик, в котором при добавлении новой записи в таблицу значение счётчика увеличивается на 1 (или другую величину).

9.Номер записи используют в качестве первичного ключа в следующих случаях:
1)	В отсутствие других естественных или уникальных идентификаторов. Если в таблице отсутствуют поля, которые однозначно идентифицируют каждую запись, то можно использовать номер записи в качестве первичного ключа.
2)	Во временных таблицах или таблицах с незначительным количеством данных. В таких случаях нецелесообразно создавать дополнительные поля для идентификации записей, и вместо этого можно использовать номер записи.
3)	В некоторых базах данных, где номер записи является встроенным и автоматически присваивается каждой новой записи при её создании.

10. Некоторые методы поиска данных:
•	Адресный поиск. Процесс поиска документов по формальным признакам, указанным в запросе. Для осуществления нужны точный адрес документа и строгий порядок его расположения в запоминающем устройстве или в хранилище системы.
•	Семантический поиск. Процесс поиска документов по их содержанию. Для этого содержание документов и запросов переводят на информационно-поисковый язык, составляют поисковые образы документа и запроса и составляют поисковое описание с дополнительным условием поиска.
•	Документальный поиск. Процесс поиска в хранилище информационно-поисковой системы первичных документов или в базе данных вторичных документов, соответствующих запросу пользователя.
•	Фактографический поиск. Процесс поиска фактов, соответствующих информационному запросу. К фактографическим данным относятся сведения, извлечённые из документов и получаемые непосредственно из источников их возникновения.
•	Полнотекстовый поиск. Поиск по всему содержимому документа. Для ускорения поиска используются предварительно построенные индексы.
•	Поиск по метаданным. Это поиск по атрибутам документа, поддерживаемым системой: название документа, дата создания, размер, автор и т. д..

11.Линейный и бинарный поиск различаются тем, что линейный проверяет каждый элемент последовательно, а бинарный делит область поиска пополам на каждом шаге.
Достоинства линейного поиска:
•	Простота реализации.Линейный поиск легко понять и написать код даже начинающему программисту.
•	Нет требований к данным. Линейный поиск может применяться к неотсортированным данным.
•	Подходит для небольших массивов. Линейный поиск эффективен для массивов небольшого размера.
Недостатки линейного поиска:
•	Низкая эффективность для больших массивов. Временная сложность O(n) делает его неэффективным для больших массивов.
•	Длительное время выполнения. Для больших массивов линейный поиск может занять много времени, особенно если искомый элемент находится ближе к концу массива или отсутствует.
Достоинства бинарного поиска:
•	Высокая эффективность для больших массивов. Временная сложность O(log n) делает его очень эффективным для больших массивов.
•	Быстрое выполнение. Бинарный поиск значительно быстрее линейного поиска при работе с большими отсортированными массивами.
Недостатки бинарного поиска:
•	Требование отсортированных данных. Бинарный поиск работает только с отсортированными массивами, что может потребовать дополнительного времени на предварительную сортировку.
•	Сложность реализации. Реализация бинарного поиска сложнее по сравнению с линейным поиском.

12.Индекс — это совокупная последовательность символов, цифр или букв, которая содержит указание на место элемента или же характеристику некого множества элементов. Образовано от латинского слова index, что в переводе значит «палец указательный», «перечень» или же «указатель».
найдено на yandex.ru
Индекс строится как отношение индексируемой величины на текущем уровне к значению индексируемой величины на базисном уровне. По степени охвата элементов явления (представляющих собой единицы совокупности) индексы разделяют на индивидуальные и сводные (общие).

13.Да, для одной и той же таблицы можно построить несколько индексов.
Например, для каждой таблицы можно создавать более одного некластеризованного индекса.

14.Принцип поиска с помощью индекса заключается в том, что индекс позволяет быстро находить строки по конкретному запросу без необходимости сканирования всей таблицы.

15.Целостность базы данных — это свойство, означающее, что она содержит полную, непротиворечивую и адекватно отражающую предметную область информацию.
Виды целостности базы данных:
1)	Физическая целостность. Означает общую защиту информации при её хранении и перемещении. К ней относятся угрозы, такие как землетрясения, наводнения, пожары, внезапные отключения электричества, неправильное обращение с оборудованием, случайное удаление информации, взломы и вирусы.
2)	Логическая целостность. Относится к правильности и точности данных в зависимости от их применения. Основная задача — сохранять данные неизменными во время их использования в реляционных базах данных. Виды логической целостности:
•	Целостность сущности. Создание первичного ключа — уникального идентификатора для каждой записи в таблице БД. Это помогает избежать дублирования информации.
•	Ссылочная целостность. Набор правил, который гарантирует единообразное использование данных в таблицах.
•	Целостность домена. Поддержание правильности данных внутри домена. Можно регулировать количество и типы значений в столбцах (например, разрешить ввод только чисел, текста или дат в формате ДД.ММ.ГГГГ).
•	Пользовательская целостность. Дополнение к целостности сущностей, ссылок и домена. Если этих типов недостаточно, компании могут перейти к целостности, определяемой пользователем.
16.Физическая целостность данных обеспечивается для защиты информации при её хранении и перемещении от различных угроз, таких как землетрясения, наводнения, пожары, внезапные отключения электричества, неправильное обращение с оборудованием, случайное удаление информации, взломы и вирусы.
17.Логическая целостность данных обеспечивается установлением правил, которые исключают модификацию данных в базе. Эти правила называются ограничениями целостности.
