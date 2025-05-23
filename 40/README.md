# 11-40
Вот ответы на ваши вопросы об операционных системах (ОС):

1. Зачем нужны операционные системы? Можно ли обойтись без них?

Зачем нужны: Операционные системы (ОС) нужны для управления аппаратными ресурсами компьютера (процессор, память, устройства ввода-вывода) и предоставления программной среды для запуска приложений. Они упрощают взаимодействие пользователя с компьютером, обеспечивают удобный интерфейс, обеспечивают безопасность и стабильность работы.
Можно ли обойтись: Теоретически, можно управлять компьютером без ОС, напрямую взаимодействуя с “железом”. Однако это крайне сложно, требует глубоких знаний программирования на низком уровне и делает использование компьютера практически невозможным для обычного пользователя. Современные компьютеры без ОС функционировать не смогут.

2. Что такое операционная система?

Операционная система (ОС) - это программное обеспечение, которое управляет аппаратными ресурсами компьютера и предоставляет среду для запуска и работы прикладных программ. Она выступает посредником между аппаратным обеспечением и пользователем/приложениями.

3. Какие задачи выполняет ОС?

Основные задачи ОС:

Управление процессом: Планирование и управление выполнением задач (процессов).
Управление памятью: Распределение и управление оперативной памятью для различных процессов.
Управление файловой системой: Организация хранения данных на дисках (файлы, каталоги).
Управление устройствами ввода-вывода: Взаимодействие с периферийными устройствами (клавиатура, мышь, принтер, монитор и т.д.) с помощью драйверов.
Обеспечение безопасности: Защита системы от несанкционированного доступа, вирусов и других угроз.
Предоставление пользовательского интерфейса: Обеспечение интерфейса для взаимодействия пользователя с компьютером (графический или командная строка).

4. Чем отличаются многозадачные ОС от однозадачных?

Однозадачные ОС: Могут выполнять только одну задачу (программу) в один момент времени. Примеры: старые версии MS-DOS.
Многозадачные ОС: Могут выполнять несколько задач одновременно (на самом деле, переключаясь между ними очень быстро). Это позволяет пользователю работать с несколькими приложениями (например, редактировать текст, слушать музыку и просматривать веб-страницы) одновременно. Современные ОС - многозадачные.

5. Как обеспечивается многозадачность на компьютерах с одним процессором?

На компьютерах с одним процессором многозадачность достигается за счет разделения времени (time-sharing). ОС быстро переключается между задачами, выделяя каждой задаче короткий интервал времени (квант времени) для выполнения. Пользователь воспринимает это как одновременное выполнение нескольких задач, хотя на самом деле процессор поочерёдно выполняет команды из разных программ.

6. Что такое пакетный режим работы?

Пакетный режим работы - это метод обработки заданий, при котором задания группируются в пакеты и запускаются без интерактивного взаимодействия с пользователем. Пользователь предоставляет задания (наборы инструкций и данных) в виде пакета, а система выполняет эти задания одно за другим. Этот режим был распространен в ранних компьютерах.

7. Что такое многопользовательский режим?

Многопользовательский режим - это возможность одновременной работы нескольких пользователей с одним компьютером. Каждый пользователь имеет свою учетную запись, свои файлы и настройки. ОС обеспечивает изоляцию данных и прав доступа для каждого пользователя, обеспечивая безопасность и конфиденциальность.

8. Перечислите составные части ОС.

Основные составные части ОС:

Ядро (Kernel): Основная часть ОС, которая управляет аппаратными ресурсами, выполняет планирование задач, управляет памятью и предоставляет базовые сервисы.
Драйверы (Drivers): Программы, обеспечивающие взаимодействие ОС с аппаратными устройствами (принтеры, видеокарты, сетевые карты и т.д.).
Системные библиотеки (System libraries): Набор функций и подпрограмм, которые предоставляют приложениям доступ к функциям ОС (например, для работы с файлами, графикой, сетью).
Утилиты (Utilities): Вспомогательные программы для обслуживания и настройки системы (например, архиваторы, дефрагментаторы, антивирусы).
Пользовательский интерфейс (User interface): Средства взаимодействия пользователя с ОС (графический интерфейс - GUI, командная строка - CLI).

9. Что такое начальный загрузчик?

Начальный загрузчик (bootloader) - это программа, которая загружается в память при включении компьютера (или перезагрузке) и отвечает за загрузку операционной системы. Он инициализирует аппаратное обеспечение, находит ядро ОС на диске, загружает его в память и передает управление ядру.

10. Что такое драйвер?

Драйвер - это программное обеспечение, которое позволяет операционной системе взаимодействовать с аппаратным устройством. Он переводит команды ОС в формат, понятный устройству, и преобразует данные, полученные от устройства, в формат, понятный ОС. Каждое устройство (принтер, видеокарта, сетевая карта и т.д.) требует своего драйвера.

11. Какие программы относятся к утилитам?

К утилитам относятся:

Архиваторы: (WinRAR, 7-Zip) для сжатия и распаковки файлов.
Дефрагментаторы: (Diskeeper, встроенные в ОС) для оптимизации расположения файлов на диске.
Антивирусы: (Dr.Web, Kaspersky, Avast) для защиты от вредоносного ПО.
Программы резервного копирования: (Acronis True Image, встроенные в ОС) для создания резервных копий данных.
Редакторы реестра: (regedit в Windows) для редактирования настроек ОС.
Диспетчер задач: (taskmgr в Windows) для мониторинга работы системы и управления процессами.
Утилиты для работы с дисками: (fdisk, parted в Linux/Unix) для разбиения дисков на разделы.

12. Какими достоинствами и недостатками обладает система UNIX?

Система UNIX (и ее производные, такие как Linux и macOS) обладает следующими достоинствами:

Стабильность и надежность: UNIX-подобные системы известны своей стабильной работой и способностью восстанавливаться после сбоев.
Многозадачность и многопользовательский режим: UNIX-системы хорошо поддерживают многозадачность и многопользовательский режим, что делает их пригодными для серверов и рабочих станций.
Гибкость и настраиваемость: UNIX-системы обладают высокой гибкостью и настраиваемостью, позволяя адаптировать их под конкретные нужды.
Безопасность: UNIX-системы разработаны с учетом вопросов безопасности, имеют хорошую систему разграничения прав доступа.
Переносимость: UNIX-системы могут работать на различных аппаратных платформах.
Мощный командный интерфейс (shell): UNIX предлагает мощный командный интерфейс с возможностью автоматизации задач и создания скриптов.
Недостатки:

Сложность освоения: Для начинающих пользователей может быть сложным освоение командного интерфейса и конфигурирование системы.
Не всегда интуитивно понятный GUI: GUI UNIX-систем (например, в Linux) может быть менее интуитивным, чем в Windows.
Проблемы совместимости (относительно Windows): Иногда возникают проблемы совместимости с некоторыми программами и драйверами, разработанными для Windows.
Требует знаний: Для эффективной работы с UNIX-системами требуются определенные знания и навыки.

13. Как ОС обменивается данными с внешними устройствами? В чём достоинства такой схемы?

ОС обменивается данными с внешними устройствами через драйверы. Когда приложение хочет выполнить операцию с устройством (например, распечатать документ на принтере), оно передает запрос ОС. ОС, в свою очередь, вызывает соответствующий драйвер устройства. Драйвер преобразует запрос в команды, понятные устройству, и отправляет их на устройство. Устройство выполняет команду и может вернуть данные (например, данные о статусе печати) обратно драйверу, который передает их ОС, а ОС - приложению.

Достоинства такой схемы:

Абстракция: Приложениям не нужно знать, как именно работает конкретное устройство. Они взаимодействуют с ОС, которая берет на себя все детали взаимодействия с устройством.
Унификация: ОС обеспечивает единый интерфейс для работы с различными устройствами, упрощая разработку приложений.
Гибкость: При замене устройства (например, на новую модель принтера), достаточно установить новый драйвер, а приложения останутся неизменными.
Переносимость: ОС может быть перенесена на другую аппаратную платформу, если для новых устройств будут разработаны соответствующие драйверы.

14. Что происходит, когда ОС обнаруживает новое устройство?

Когда ОС обнаруживает новое устройство (например, при подключении USB-устройства):

ОС определяет тип устройства: ОС пытается определить тип устройства (например, флеш-накопитель, принтер, мышь).
Поиск драйвера: ОС ищет подходящий драйвер для этого устройства в своей базе данных или предлагает пользователю установить драйвер с диска, из интернета или из архива.
Установка драйвера: Если драйвер найден (или установлен), ОС загружает его в память.
Инициализация устройства: ОС использует драйвер для инициализации устройства, отправляя ему команды для настройки и подготовки к работе.
Устройство готово к работе: После инициализации устройство становится доступным для использования приложениями. ОС может начать обрабатывать запросы от приложений к этому устройству.

15. Что такое файловая система? Зачем она нужна?

Файловая система (ФС) - это способ организации, хранения и доступа к данным на диске или другом носителе информации. Она определяет, как файлы и каталоги (папки) хранятся, как организованы, как к ним осуществляется доступ и как распределяется дисковое пространство.

Файловая система нужна для:

Организации данных: Файловая система обеспечивает структурированное хранение данных, позволяя пользователям организовывать информацию в файлы и каталоги.
Управления дисковым пространством: ФС отслеживает, какие участки диска заняты, а какие свободны, и обеспечивает эффективное использование дискового пространства.
Обеспечения доступа к данным: ФС предоставляет интерфейс для доступа к файлам, позволяя пользователям читать, записывать, изменять и удалять данные.
Защиты данных: ФС может включать механизмы для защиты данных от несанкционированного доступа (права доступа, шифрование).
Повышения производительности: ФС оптимизирует размещение файлов на диске для ускорения доступа к ним.

16. Какие задачи решает файловая система?

Файловая система решает следующие задачи:

Хранение файлов: Организует хранение данных в виде файлов.
Организация каталогов: Позволяет создавать каталоги (папки) для организации файлов в иерархическую структуру.
Управление дисковым пространством: Распределяет дисковое пространство между файлами и каталогами, отслеживает занятое и свободное пространство.
Размещение файлов: Определяет местоположение файлов на диске (кластеры, секторы).
Управление доступом: Обеспечивает контроль доступа к файлам и каталогам (права доступа для пользователей и групп).
Метаданные: Хранит метаданные о файлах (имя, размер, дата создания, дата изменения, атрибуты).
Обеспечение целостности данных: Обеспечивает целостность данных (например, путем использования механизмов журналирования).

17. Что такое кластер?

Кластер - это минимальная единица дискового пространства, выделяемая файловой системой для хранения файла или его части. Кластер состоит из одного или нескольких смежных секторов диска. Когда файл записывается на диск, он занимает один или несколько кластеров.

18. Почему невыгодно хранить мелкие файлы в файловой системе с большим размером кластера?

Потому что при большом размере кластера даже для хранения небольшого файла будет выделен целый кластер. Например, если размер кластера 4 КБ, а файл занимает всего 100 байт, то остальная часть кластера (около 3900 байт) будет неиспользованной, что приводит к неэффективному использованию дискового пространства.

19. Что улучшается при увеличении размера кластера?

Ускорение операций чтения/записи крупных файлов: При чтении/записи больших файлов с использованием больших кластеров уменьшается количество обращений к диску, что может привести к ускорению работы.
Сокращение фрагментации: Меньше фрагментации, так как файлы занимают более крупные непрерывные участки диска.
Однако, увеличение размера кластера имеет и недостатки (см. вопрос 18).

20. Какие файловые системы используются в ОС Windows, Linux/Unix и macOS?

Windows:

NTFS (New Technology File System) - основная файловая система для современных версий Windows.
FAT32 (File Allocation Table 32) - устаревшая файловая система, совместимая с большинством ОС, но с ограничениями (максимальный размер файла 4 ГБ, максимальный размер раздела 2 ТБ).
exFAT (Extended File Allocation Table) - файловая система, разработанная Microsoft для флеш-накопителей, имеет меньшие ограничения, чем FAT32.
Linux/Unix:

ext4 (Fourth Extended Filesystem) - наиболее распространенная файловая система.
ext3 (Third Extended Filesystem) - предшественница ext4.
XFS - высокопроизводительная файловая система, часто используемая для серверов.
Btrfs - современная файловая система с поддержкой снимков (snapshots), сжатия данных и другими продвинутыми функциями.
macOS:

APFS (Apple File System) - современная файловая система, разработанная Apple.
HFS+ (Hierarchical File System Plus) - устаревшая файловая система, использовалась в предыдущих версиях macOS.

21. Почему файловая система FAT32 считается устаревшей?

FAT32 считается устаревшей по следующим причинам:

Ограничения на размер файла: Максимальный размер файла - 4 ГБ, что является серьезным ограничением для современных файлов (например, видео, образы дисков).
Ограничения на размер раздела: Максимальный размер раздела - 2 ТБ.
Отсутствие журналирования: FAT32 не поддерживает журналирование, что делает ее более уязвимой к повреждениям данных в случае сбоев питания или ошибок записи.
Низкая производительность: FAT32 имеет более низкую производительность, чем современные файловые системы, такие как NTFS, ext4 и APFS.
Отсутствие продвинутых функций: FAT32 не поддерживает такие функции, как сжатие данных, шифрование, снимки и другие современные возможности, которые есть в других файловых системах.

22. Что такое одноуровневая и многоуровневая файловые системы?

Одноуровневая файловая система: Все файлы хранятся непосредственно в корневом каталоге. Не имеет иерархии каталогов. Практически не используется в современных системах из-за плохой организации.
Многоуровневая файловая система: Файлы организованы в иерархическую структуру каталогов (папок). Каталоги могут содержать другие каталоги (подкаталоги) и файлы. Это позволяет упорядочивать данные логически и упрощает поиск файлов. Все современные файловые системы - многоуровневые.

23. Что такое корневой каталог?

Корневой каталог - это основной (самый верхний) каталог в иерархической структуре файловой системы. Он содержит все остальные каталоги и файлы. В ОС Linux/Unix корневой каталог обозначается символом /. В Windows корневой каталог обычно обозначается буквой диска (например, C:\).

24. В чём различие файловых систем в ОС Linux/Unix и Windows?

Основные различия:

Структура каталогов:

Linux/Unix: Единая иерархическая структура, начинающаяся с корневого каталога /. Все устройства и ресурсы (диски, принтеры, сетевые ресурсы) монтируются в эту иерархию.
Windows: Множество корневых каталогов, по одному на каждый логический диск (C:, D:\ и т.д.).
Разделители в пути к файлу:

Linux/Unix: / (прямой слеш).
Windows: \ (обратный слеш).
Регистр имени файлов и каталогов:

Linux/Unix: Регистр имеет значение (file.txt и File.txt - разные файлы).
Windows: Регистр не имеет значения (file.txt и File.txt - один и тот же файл, но в некоторых случаях может сохранять регистр).
Права доступа:

Linux/Unix: Более гибкая система прав доступа к файлам и каталогам, основанная на пользователях, группах и разрешениях (чтение, запись, выполнение).
Windows: Система прав доступа проще, основана на пользователях и группах, но также имеет различные типы разрешений.
Метаданные:

Linux/Unix: Хранит более разнообразные метаданные о файлах.
Файловые системы по умолчанию:

Linux/Unix: ext4 (основная), XFS, Btrfs.
Windows: NTFS (основная).

25. Где расположены каталоги пользователей в ОС Linux/Unix?

В большинстве дистрибутивов Linux/Unix, каталоги пользователей обычно расположены в каталоге /home. Каждый пользователь имеет свой подкаталог в /home, имя которого соответствует имени пользователя (логину). Например, пользователь с именем user1 будет иметь свой домашний каталог /home/user1.

26. Какие символы используются как разделители при записи адреса файла в ОС Linux/Unix и Windows?

Linux/Unix: / (прямой слеш)

Пример: /home/user1/Documents/report.txt
Windows: \ (обратный слеш)

Пример: C:\Users\user1\Documents\report.txt

27. Что такое сетевая файловая система?

Сетевая файловая система - это файловая система, которая позволяет получать доступ к файлам, хранящимся на другом компьютере в сети. Она позволяет пользователям работать с файлами, расположенными удаленно, как если бы они находились на локальном компьютере. Сетевая файловая система предоставляет прозрачный доступ к файлам, используя протоколы сетевого взаимодействия.

Примеры сетевых файловых систем:

NFS (Network File System): широко используется в Linux/Unix.
SMB/CIFS (Server Message Block / Common Internet File System): используется в Windows (также поддерживается в Linux/Unix).
AFP (Apple Filing Protocol): используется в macOS.
FTP (File Transfer Protocol): протокол для передачи файлов, но также может использоваться для организации доступа к файлам.
WebDAV (Web Distributed Authoring and Versioning): протокол, основанный на HTTP, для доступа к файлам через интернет.
