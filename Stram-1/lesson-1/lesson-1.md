# Занятие 1. Введение в CtF
На этом занятии подробно раскрывается термин CtF и рассматриваются виды соревнований и распространенных тасков.

## Что такое CTF
CTF (Capture The Flag) - это соревнования в области информационной безопасности, в которой участники стремятся найти и захватить флаги, представляющие собой секретные коды или файлы. В ходе соревнования участникам предлагаются разнообразные задания, проверяющие их знания и навыки в самых различных категориях. CTF не только позволяет участникам развивать свои навыки, но и способствует обмену знаниями и опытом в сообществе. Это захватывающий процесс, стимулирующий участников продемонстрировать интеллект и креативность в решении сложных задач.

## Цели и задачи CTF-соревнований
Основные цели и задачи CTF-соревнований заключаются в развитии и проверке навыков участников в области информационной безопасности. Среди самых популярных категорий заданий можно выделить криптографию, веб-эксплуатацию, реверс-инжиниринг и другие.

В ходе соревнований участники развивают умение анализировать и исследовать разнообразные системы, выявлять уязвимости и пытаться эксплуатировать их.. Они также улучшают свои навыки в области решения задач, постановки приоритетов и управления временем. CTF-соревнования позволяют участникам приобрести практический опыт в области информационной безопасности, применить полученные знания на практике и познакомиться с новыми инструментами и технологиями. Кроме того, соревнования способствуют обмену опытом и знаниями между участниками и профессионалами в области информационной безопасности. Подобные мероприятия расширяют кругозор участников, повышают квалификацию и готовят их к решению аналогичных задач в реальных условиях.

## Основные виды CTF-соревнований
CTF-соревнования выделяются двумя популярными форматами - Jeopardy и Attack-Defense. Оба формата несколько отличаются друг от друга. Ниже мы разберем их основные отличия.

### Jeopardy
Jeopardy (или Task Based) стиль является одним из самых распространенных и популярных. В этом формате команды участников выполняют разнообразные задания в нескольких категориях, среди них: криптография, веб-эксплуатация, реверс-инжиниринг, стеганография и многие другие.

Задачи могут представлять собой криптографические головоломки, веб-приложений с уязвимостями, программных файлов, сетевых задач и т.д. Решая задачи, участники набирают баллы, зависящие от уровня сложности.

Правильным ответом или верным ответом считается флаг в форме набора символов или произвольной фразы. За каждый найденный и сданный флаг, команда получает определенное количество очков, которое определяет рейтинг команды в турнирной таблице. Чем сложнее таск (задание), тем больше очков даётся за правильный ответ.

### Attack-Defense
В Attack-Defense (Атака-Защита) команда участников разделяется на две группы: атакующие (red team) и защищающиеся (blue team). Атакующие участники пытаются найти уязвимости в защищаемых системах и эксплуатировать их, чтобы получить доступ к ценной информации или контролировать систему. С другой стороны, защищающиеся участники должны обнаруживать и устранять уязвимости, предотвращать несанкционированный доступ и защищать систему от атак. Система рейтинга в соревнованиях формата Attack-Defense обычно работает по такой схеме: атакуете вы - получаете очки, атакуют вас - теряете их.

В соревнованиях данного формата используются реалистичные системы и сервисы, такие как веб-приложения, базы данных, сетевые сервисы и операционные системы. Участники могут использовать известные им методы и инструменты для проведения атак и защиты, включая программирование, эксплойты, обнаружение уязвимостей, криптографию и многое другое.

Цель Attack-Defense соревнований - повысить навыки участников в области информационной безопасности, позволить им успешно практиковать полученные знания в реальном мире и узнать о новых уязвимостях и методах атаки. Это также способ привлечь внимание к важности безопасности информации и поощрить развитие новых методов защиты.

Для атаки на команду противника вам потребуется знать её IP-адрес. Обычно организаторы предоставляют диапазон игровых IP-адресов или показывают адреса команд в scoreboard’е. Выбрав цель, вы входите в панель администрирования на её IP-адресе с использованием стандартного пароля, найденного вами. Если удачно войдете, приступайте к поиску флагов!

## Категории заданий в CTF
Задания в CTF могут быть разделены на несколько категорий, каждая из которых фокусируется на определенных аспектах информационной безопасности. Ниже приведены основные категории заданий:

- Криптография (Cryptography): Эта категория заданий в CTF связана с шифрованием и дешифрованием сообщений, анализом криптографических алгоритмов и поиском уязвимостей в криптографических системах.

- Веб-эксплуатация (Web Exploitation): Задания в этой категории связаны с поиском и эксплуатацией уязвимостей веб-приложений, таких как инъекции, обход аутентификации, межсайтовый скриптинг (XSS) и другие уязвимости, связанные с веб-технологиями.

- Реверс-инжиниринг (Reverse Engineering): В этой категории участникам предстоит анализировать исполняемый код, такой как бинарные файлы или программы, и понимать его структуру, функциональность и уязвимости путем обратного проектирования и отладки.

- Форензика (Forensics): Задания в этой категории требуют анализа цифровых следов и расследования инцидентов. Участники могут столкнуться с такими задачами как восстановление удаленных файлов, анализ метаданных, поиск скрытых сообщений и другими методами цифрового расследования.

- Стеганография (Steganography): Задания в этой категории связаны со скрытой передачей информации внутри других файлов или медиа-контента. Участникам предлагается найти и извлечь скрытые сообщения из изображений, аудио или видео файлов, анализ методов стеганографии и поиск уязвимостей в таких методах.

- OSINT (Open Source Intelligence): Задания связаны со сбором информации из открытых источников. Для решения подобных заданий требуется умение поиска и анализа общедоступных данных, исследование персон, поиск уязвимостей в системах на основе открытой информации и т.д.

- PWN: Задания в этой категории связаны с эксплуатацией уязвимостей программного обеспечения, таких как переполнение буфера, исполнение кода, обход ограничений и другие методы атаки на программы.

- Развлечения (Miscellaneous): В этой категории задания являются разнообразными и не подпадают под основные категории. Они могут включать головоломки, шифры, геокэшинг, ребусы и и прочие неординарные задания.

- Квесты / Машины: В этой категории можно встретить задания из сразу нескольких категорий, а так же ключевыми этапами в большинстве таких заданий является повышение привилегий по схеме www-data → user → root, т.е. забирать флаги придется на разных уровнях доступа.

- Active Directory: В заданиях из данной категории предлагается исследовать корпоративные сети, использовать различные методы для пошагового расширения своих привилегий и получения полного контроля над доменом.

## Виды и типы флагов
Флаги в CTF (Jeopardy/Attack-Defense) могут быть разных типов и форматов.

Каждый флаг является уникальным, и как правило формат представляет собой название_ивента{флаг}, к примеру, CODEBY{th1s_1s_a_f4k3_fl4g}. Под Ивентом (Event) в нашем случае понимается CTF-соревнование. В некоторых случаях флаги могут быть закодированы с использованием Base32, что означает, что они представлены в виде текстовой строки, содержащей только символы из алфавита Base32 (A-Z, 2-7).

## Глоссарий
**Jeopardy**
- Таск - задание в определенной категории, которую нужно решить/взломать/разгадать для получения флага
- Флаг - уникальный код или строка, которую участники должны найти или получить, чтобы доказать, что они решали определенное задание. Пример: CODEBY{th1s_1s_a_f4k3_fl4g}
- Описание - может содержать информацию о цели задания, правилах, флаге, который нужно найти, и других подсказках или инструкциях, которые помогут участникам выполнить задание. Описание может быть представлено в виде текстового файла, веб-страницы, изображения или любого другого формата, который организаторы выберут для передачи информации участникам.
- Хинт (от англ. hint) — это подсказка или небольшая информация, предоставляемая участникам для помощи в решении задания
- Очки (от англ. points) — численное значение, которое увеличивается при сдаче флага, что способствует повышению в турнирной таблице.
- Скорборд (от англ. scoreboard) — это таблица, на которой отображается текущее положение команд или участников в соревновании. Скорборд обычно показывает количество набранных очков каждой команды или участника, обновляется в реальном времени и может быть доступен для всех участников, чтобы следить за прогрессом других команд. </br> </br>
**Attack-Defense**
- Vulnbox (игровой сервер / уязвимый образ) — физический / виртуальный сервер, на котором размещаются сервисы команды.
- Сервис — уязвимое приложение, которое функционирует через сеть и развернуто на vulnbox’e. Обычно на одном соревновании присутствует несколько сервисов.
- SLA (Service Level Agreement) — доля пройденных игровых раундов со статусом OK для данного сервиса к общему количеству пройденных раундов. Обычно измеряется в процентах.
- FP (Flag Points) — численное значение, которое увеличивается при захвате флаг и уменьшается, когда их захватывают у вас.
- Флаг — строка, являющаяся частью конфиденциальных данных в сервисе. Обычно соответствует регулярному выражению [A-Z0-9]{31}=.
- Раунд — заданный временной интервал, единица времени в игре.
- Чекер - специальная программа, которую организаторы CTF-соревнований запускают для проверки работоспособности сервиса. Чекер эмулирует действия пользователя в сервисе и проверяет, выполняются ли все необходимые условия. При успешной проверке, чекер оставляет флаги, которые могут быть использованы для подтверждения правильности решения задачи.
- Атака — процесс захвата флагов с чужих сервисов.
- Защита — устранение обнаруженной уязвимости, после чего использование ее для атак становится невозможным.
- Эксплойт — программа, которая автоматически занимается захватом флагов через обнаруженную уязвимость.
- Скорборд (Scoreboard) - это приложение, которое отображает текущую позицию команд в турнирной таблице.

## CTF-инструментарий
Инструменты и утилиты являются важными и неотъемлемыми помощниками участников CTF-соревнований. Чаще всего на них возлагаются задачи автоматизации повторяющихся процессов, упрощения взаимодействие с сервисами и службами, расширения возможностей имеющегося софта. Использование open-source и самописных утилит позволяет участникам сосредоточиться на более сложных и интересных задачах. </br> </br>

**Active Directory**
1. impacket-GetNPUsers - позволяет получить список пользователей в Active Directory.
1. enum4linux-ng - используется для сканирования системы и получения информации о ней.
1. evil-winrm - позволяет подключиться к системе по протоколу WinRM.
1. ldapsearch - используется для поиска информации в LDAP-каталоге.
1. crackmapexec - позволяет проверить уязвимости в системах.
1. kerbrute - используется для брутфорса и перебора учетных записей в Active Directory.
1. smbclient - позволяет подключиться к системе по протоколу SMB.
1. bloodhound - используется для анализа связей в Active Directory.
1. adalanche - аналогичен bloodhound и используется для анализа связей в Active Directory. </br> </br>
**Квесты**
1. linpeas - автоматизирует процесс поиска уязвимостей в Linux-системах.
1. linux-exploit-suggester - помогает найти уязвимости в Linux-системах.
1. pspy - позволяет просматривать процессы и их привилегии в Linux-системах.
1. GTFOBins - онлайн-сервис со списком двоичных файлов Unix, которые можно использовать для повышения привилегий на неправильно сконфигурированных системах. </br> </br>
**Веб**
1. Burp Suite - мощнейший расширяемый фреймоврк для тестирования приложений, которая включает в себя такие инструменты, как прокси-сервер, сканер уязвимостей, fuzzer и другие.
1. OWASP ZAP - свободно распространяемый инструмент, который включает в себя такие инструменты, как прокси-сервер, сканер уязвимостей, fuzzer и другие.
1. sqlmap - инструмент для автоматического обнаружения уязвимостей в SQL запросах и эксплуатации SQL-инъекций. Наверное так будет корректнее.
1. Nikto - сканер уязвимостей веб-серверов, который проверяет сервер на наличие уязвимостей и устаревших компонентов.
1. DirBuster - утилита для автоматического обнаружения скрытых файлов и каталогов на веб-сервере.
1. Wfuzz - инструмент для автоматического fuzz-тестирования веб-приложений.
1. Nmap/Zenmap - сетевой сканер, который может быть использован для обнаружения открытых портов и сервисов.
1. Acunetix, Nuclei - автоматические сканеры веб-приложений, которые включают в себя такие функции, как сканирование SQL-инъекций, XSS, CSRF и других уязвимостей.
1. Chrome DevTools - встроенный в браузер Chrome инструмент для разработчиков, который включает в себя такие функции, как отладка JavaScript, просмотр сетевого трафика и другие.
1. XSSer - утилита для автоматического обнаружения уязвимостей XSS (Cross-Site Scripting) на веб-сайтах. </br> </br>
**Стеганография**
1. Convert - конвертация изображений в различные форматы и применение к ним фильтров
1. Exif - отображение информации EXIF в файлах JPEG
1. Exiftool - чтение и запись метаданных в файлах
1. Exiv2 - инструмент для работы (модифицирования) метаданными изображений
1. ImageMagick - инструмент для создания, обработки и редактирования изображений
1. Outguess - универсальный инструмент для реализации задач стеганографии
1. Pngtools - утилита используемая для исследования PNG файлов
1. SmartDeblur - используется для восстановления размытых изображений
1. Steganabara - инструмент для анализа стеганографии, написанный на Java
1. Stegbreak - утилита для поиска, выявления и модификации стеганографических включений в изображениях
1. StegCracker - утилита для нахождения скрытых данных внутри файлов
1. stegextract - обнаружение скрытых файлов и текста в изображениях
1. Steghide - скрытие данных в различных типах изображений
1. Stegsolve - применение различных стеганографических методов к изображениям
1. Zsteg - анализ PNG/BMP
1. Stego-Toolkit - как принято говорить, “все в одном” </br> </br>
**Форензика**
1. Audacity - анализ звуковых файлов (mp3, m4a и т.д.)
1. Bkhive и Samdump2 - извлечение файлов SYSTEM и SAM
1. Creddump - извлечение учетных данных Windows
1. Exif Tool - чтение, запись и редактирование метаданных файлов
1. Extundelete - восстановление утерянных данных из монтируемых изображений
1. Foremost - инструмент для восстановления определенного типа файлов на основе заголовков
1. Fsck.ext4 - исправление поврежденных файловых систем
1. Malzilla - инструмент для поиска вредоносных программ
1. NetworkMiner - инструмент для анализа сетевого трафика и поиска в нём файлов различного типа
1. PDF Streams Inflater - нахождение и извлечение файлов zlib, сжатых в PDF-файлах
1. ResourcesExtract - извлечение различных типов файлов из исполняемых файлов
1. Shellbags - исследование файлов NT_USER.dat
1. UsbForensics - содержит набор инструментов для анализа USB
1. Volatility - для исследования сниппейтов памяти </br> </br>
**Криптография**
1. FeatherDuster - автоматизированный, модульный инструмент для криптоанализа
1. Hash Extender - утилита для выполнения атак на расширение хэша
1. PkCrack - инструмент для взлома шифрования PkZip
1. RSACTFTool - утилита для восстановления закрытого ключа RSA с помощью различных атак
1. RSATool - программа для работы с РСА
1. XORTool - инструмент для анализа многобайтового шифра XOR
1. John the Ripper - инструмент для взлома хэшей
1. Hashcat - инструмент для взлома хэшей </br> </br>
**Реверс-инжиниринг**
1. IDA Pro - интегрированная среда разработки для анализа и декомпиляции программ.
1. dnSpy - декомпилятор и дизассемблер и отладчик для платформы .NET.
1. ByteCode Viewer - инструмент для анализа байт-кода Java-приложений, используя различные декомпиляторы. Open Source.
1. jadx - декомпилятор DEX-файлов, JAR и APK-файлов в исходный код. Open Source.
1. PyInstaller Extractor - скрипт для извлечения содержимого EXE-файла, созданного PyInstaller. Open Source.
1. uncompyle6 - декомпилятор байт-кода Python (файлы PYC). Open Source.
1. Frida - инструмент для динамического анализа и манипулирования с исполняемыми файлами, процессами и системами. Open Source.
1. Ghidra - платформа для анализа и декомпиляции программ, разработанная АНБ.
1. Radare2 - свободная и открытая платформа для анализа и декомпиляции программ.
1. OllyDbg - отладчик для операционной системы Windows
1. x64dbg - программа для отладки приложений и программ, разработанных 32⁄64 разрядной архитектурах
1. WinDbg - многоцелевой отладчик для Windows
1. GDB - переносимый отладчик проекта GNU для программ написанных на C/C++ </br> </br>
**PWN**
1. GDB - инструмент для отладки программ.
1. Radare2 - платформа для анализа и декомпиляции программ.
1. pwntools - библиотека для автоматизации процесса взлома программ.
1. AFL - фреймворк для автоматического обнаружения уязвимостей.
1. Angr - фреймворк для анализа безопасности программ.
1. QEMU - эмулятор процессора.
1. GDB-PEDA - плагин для GDB.
1. ROPgadget - инструмент для поиска кодовых кусков.
1. PeachPy - библиотека на языке Python для работы с ассемблером.
1. AFL - фреймворк для автоматического обнаружения уязвимостей (фаззинг). </br> </br>

Это далеко не полный список инструментов, но для первых шагов в CTF такого набора будет более чем достаточно. Выбор инструментов зависит от конкретного задания и уровня сложности, надеюсь, что список выше поможет вам быстрее и проще ориентироваться в таком обилии средств. Кроме того, важно понимать, что инструменты - это только инструменты, они не могут заменить знания и опыт. Важно развивать свои навыки, изучать различные технологии, научиться понимать, как работают различные системы и протоколы. Именно это и будет залогом успеха в решении CTF-задач