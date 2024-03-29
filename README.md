# Целевая страница
## 1. Проект

### 1.1 Рассматриваемая система (процесс)

#### 1.1.1 Наименование: Взять книгу в библиотеке

#### 1.1.2 Цель (назначение): Узнать местонахождение книги, взять книгу на своё имя

#### 1.1.3 Разбор цели системы по SMART
|Критерий|Значение|Оценка|
|--|--|--|
|S (конкретность)|Читатель получает книгу|✅|
|M (измеримость) | |❌|
|A (достижимость)|Библиотекарь с картотекой|✅|
|R (уместность)  |Нахождение книг в библиотеке|✅|
|T (ограниченность во времени)|Время работы библиотеки|✅|

### 1.2 Предлагаемый проект

#### 1.2.1 Наименование: Проектирование системы для выбора книги в библиотеке

#### 1.2.2 Цель (изменяемый критерий SMART цели системы): Автоматизировать оборот книг в библиотеке

#### 1.2.3 Разбор цели проекта по SMART
|Критерий|Значение|Оценка|
|--|--|--|
|S (конкретность)|Читатель получает книгу|✅|
|M (измеримость) |Динамика взятия книг фиксируется в системе|✅|
|A (достижимость)|Читатель или библиотекарь с сайтом библиотеки|✅|
|R (уместность)  |Нахождение книг в библиотеке и доступ к сайту|✅|
|T (ограниченность во времени)| Время работы библиотеки|✅|

### 1.3 Вид прототипа
- [x] горизонтальный (сценарии работы)
- [ ] вертикальный (структура продукта)
- [ ] одноразовый (исследовательский)
- [x] инкрементный (эволюционный)

### 1.4 Задача

#### 1.4.1 [репозиторий](https://github.com/BorAlex7/FriedDumplings)

#### 1.4.2 [landing page](https://github.com/BorAlex7/FriedDumplings/wiki/%D0%A6%D0%B5%D0%BB%D0%B5%D0%B2%D0%B0%D1%8F-%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0-(%D1%88%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0))

#### 1.4.3 [пользовательская история](https://github.com/BorAlex7/FriedDumplings/issues)
- <Кто: главный библиотекарь>
- <Как: заказчик>
- <Хочу: автоматизировать процесс получения книги в библиотеке>
- <Чтобы: повысить книгооборот>
- <Приемка: не стоять в очереди к библиотекарю за книгой>

### 1.5 Проектные риски (спринт)

1. **Дефицит специалистов**
2. ~~Нереалистичные сроки и бюджет~~
3. **Реализация несоответствующей функциональности**
4. **Разработка неправильного пользовательского интерфейса**
5. ~~«Золотая сервировка», перфекционизм, ненужная оптимизация и оттачивание деталей~~
6. **Непрекращающийся поток изменений**
7. ~~Нехватка информации о внешних компонентах, определяющих окружение системы или вовлечённых в интеграцию~~
8. **Недостатки в работах, выполняемых внешними (по отношению к проекту) ресурсами**
9. ~~Недостаточная производительность получаемой системы~~
10. ~~Разрыв между квалификацией специалистов и требованиями проекта~~

|Вид риска|Название риска (описание события)|Вероятность|Стратегия|Мероприятие|
|--|--|--|--|--|
|1|Участник команды заболеет|🟡|Передача (Transference)|Имеющуюся задачу направить заместителю участника команды
|3|Задача по выполнению поставлена некорректно|🟢|Снижение (Mitigation)|Пересмотреть подход к выполнению задачи и сформулировать ее корректно
|4|Интерфейс не имеет или имеет функции, которые соответствуют пользователю|🟡|Снижение (Mitigation)|Пересмотреть функции пользователей и подкорректировать интерфейс
|6|При выполнении спринта появятся новые задачи|🟡|Уклонение (Avoidance)|Запретить принимать новые задачи в sprint log
|8|Возникла проблема с незнанием работы, которую выполняешь|🟡|Уклонение (Avoidance)<br>Передача (Transference)<br>Принятие (Acceptance)|Спросить помощи или передать работу знающему участнику

## 2. Команда
### 2.1. Закрепление полномочий
| Роль	| Ответственность (компетенция, зона принятия решений) | Менеджер | Заместитель |
|--|--|--|--|
| РП (Владелец продукта) | Бизнес-результат, решение проблем, обеспечение ресурсами | [Борисова Александра Сергеевна](https://github.com/BorAlex7) | [Клишина Анастасия Вадимовна](https://github.com/AV-Klishina)
| АД (Мастер) | Диспетчирование и контроль задач, выявление проблем| [Борисова Александра Сергеевна](https://github.com/BorAlex7) | 
| СП (Аналитик) | Сбор и управление всеми требованиями в проекте| [Маргита Елизавета Владимировна](https://github.com/Bublock) | [Клишина Анастасия Вадимовна](https://github.com/AV-Klishina)
| ВН (Дизайнер)	| Удобство использования, привлекательность продукта| [Силенок Даниил Витальевич]() | [Шавыкина Таисия Сергеевна](https://github.com/pumpurik)
| БА (Тестировщик) | Выявление бизнес-проблем, способы тестирования| [Маргита Елизавета Владимировна](https://github.com/Bublock) | [Бириков Максим Сергеевич]()
| НИ (Архитектор) | Структура продукта, инструменты разработки и поставки| [Шавыкина Таисия Сергеевна](https://github.com/pumpurik) | [Силенок Даниил Витальевич]()
| ПП (Программист) | Стиль и способы разработки, используемые фреймворки| [Шавыкина Таисия Сергеевна](https://github.com/pumpurik) | [Борисова Александра Сергеевна](https://github.com/BorAlex7)
| КО (Тех.писатель) | Документирование проекта и продукта| [Клишина Анастасия Вадимовна](https://github.com/AV-Klishina) | [Бириков Максим Сергеевич]()

### 2.2. Закрепление обязанностей

| Участник               | Стадия     | Действие (activity)             | Ожидаемый результат |
| ---------------------- | ---------- | ------------------------------- | --------------------|
| РП (Владелец продукта) | 1 старт    | Регистрирует участников проекта | Участники приняли приглашения и подключились к проекту |
| РП (Владелец продукта) | 2 контроль | Принимает решение по всем возникающим проблемам | Комментарии к проблемам (issue) |
| РП (Владелец продукта) | 3 финиш    | Принимает решение об успешности спринта, дает общую оценку работы команды и дает предложения по всем индивидуальным оценкам | Предложения по индивидуальным оценкам |
| АД (Мастер) | 1 старт|Получает оценку времени для каждой подзадачи, собирает sprint log, назначает исполнителей | Список подзадач на канбан-доске
| АД (Мастер) | 2 контроль|Проводит stand-up совещание|Статус задач отмечен на канбан-доске, проблемы зарегистрированы и назначены РП в форме дополнительных задач (issue)
| АД (Мастер) | 3 финиш|Проводит stand-up совещание|Статус задач отмечен на канбан-доске, проблемы зарегистрированы и назначены РП в форме дополнительных задач (issue)
| АД (Мастер) | 3 финиш|Проводит демонстрацию результатов спринта владельцу продукта и другим заинтересованным лицам|Протокол демонстрации записан в виде комментария к пользовательской истории
| СП (Аналитик) | 1 старт|Регистрирует историю как отдельную задачу проекта (issue)|Задача с номером
| СП (Аналитик) | 2 контроль|Регистрирует возникающие дополнительные задачи (issue) в соответствующих проектах|Задачи с номером
| СП (Аналитик) | 3 финиш|Выполняет все разработанные тесты, регистрирует все выявленные несоответствия требованиям|Задачи с номером, комментарии
| ВН (Дизайнер)	| 1 старт|Разбивает задачу истории на подзадачи - страницы|Список подзадач с именами страниц
| ВН (Дизайнер)	| 2 контроль|Разрабатывает процедуры - страницы, стили и заглушки обработчиков	html-страницы с обработчиками событий
| ВН (Дизайнер)	| 3 финиш|Разрабатывает и отлаживает процедуры - страницы, позволяющие выполнять тесты в интерактивном режиме	html-страницы и js-процедурами для запуска тестов
| БА (Тестировщик) | 1 старт|Разбивает задачу истории на подзадачи - тесты|Список подзадач с именами тестов
| БА (Тестировщик) | 2 контроль|Разрабатывает процедуры - тесты и тестовые наборы данных|html-страницы с тестами
| БА (Тестировщик) | 3 финиш|Разрабатывает и отлаживает процедуры - тесты и тестовые наборы данных|html-страницы с js-процедурами тестов и тестовые наборы данных
| НИ (Архитектор) | 1 старт|Разбивает задачу истории на подзадачи - процедуры|Список подзадач с именами процедур
| НИ (Архитектор) | 2 контроль|Определяет дополнительные требования к выполнению задач|Комментарии к задачам
| НИ (Архитектор) | 3 финиш|Принимает решение по всем выявленных несоответствиям требованиям|Комментарии к задачам
| ПП (Программист)       | 1 старт    | Разрабатывает алгоритмы выполнения всех подзадач, требующих программной реализации | Описание алгоритма и диаграмма деятельности в комментариях к задаче, в виде вики-страницы или в виде комментариев в файле программы |
| ПП (Программист)       | 2 контроль | Разрабатывает процедуры - обработчики и генераторы тестовых наборов данных | js-модули |
| ПП (Программист)       | 3 финиш    | Разрабатывает и отлаживает процедуры - генераторы тестовых наборов данных | js-модули | 
| КО (Тех.писатель) | 1 старт|Делает описания для всех подзадач, требующих программной реализации|Описание и необходимые диаграммы в комментариях к задаче, в виде вики-страницы или в виде комментариев в файле программы
| КО (Тех.писатель) | 2 контроль|Корректирует или делает новые описания для всех разработанных процедур|Описание и необходимые диаграммы в комментариях к задаче, в виде вики-страницы или в виде комментариев в файле программы
| КО (Тех.писатель) | 3 финиш|Разрабатывает требуемые описания всех разработанных процедур, тестов и тестовых наборов данных|Описание и необходимые диаграммы в комментариях к задаче, в виде вики-страниц или в виде комментариев в файлах процедур, тестов и тестовых наборов данных

### 3. Личные риски (на спринт)

1. ~~Дефицит специалистов~~
2. ~~Нереалистичные сроки и бюджет~~
3. **Реализация несоответствующей функциональности**
4. **Разработка неправильного пользовательского интерфейса**
5. **«Золотая сервировка», перфекционизм, ненужная оптимизация и оттачивание деталей**
6. ~~Непрекращающийся поток изменений~~
7. ~~Нехватка информации о внешних компонентах, определяющих окружение системы или вовлечённых в интеграцию~~
8. **Недостатки в работах, выполняемых внешними (по отношению к проекту) ресурсами**
9. ~~Недостаточная производительность получаемой системы~~
10. **Разрыв между квалификацией специалистов и требованиями проекта**

|Роль|Фаза|Вид риска|Название риска (описание события)|Вероятность|Стратегия|Мероприятие|
|--|--|--|--|--|--|--|
| ПП (Программист)| 2 контроль |3|Функция не соответствует заданной|🟡|Уклонение (Avoidance)|Проанализировать ошибку и исправить функцию
| ВН (Дизайнер)<br>ПП (Программист)| 2 контроль |4|Интерфейс не соответствует требованиям|🟡|Уклонение (Avoidance)<br>Снижение (Mitigation)|Спросить совета у команды и внести изменения в интерфейс пользователя
| ВН (Дизайнер)<br>ПП (Программист)| 2 контроль |5|Добавление лишних функций и слишком запутанный дизайн|🟡|Снижение (Mitigation)|Спросить совета у команды
| ПП (Программист)| 1 старт |8|Нет опыта в работе создания выбранного приложения|🟢|Уклонение (Avoidance)<br>Передача (Transference)|Изучить нужную литературу или передать свою задачу другому члену команды
| АД (Мастер)| 1 старт |10|Умения участника команды не соответствуют задачам, которые ему даны|🟡|Передача (Transference)|Собраться командой и определить, кто что может сделать, чтобы выдать правильные задачи

# Деловая игра
## 1. Управление командой

### 1.1. [Создание Kanban-доски и фиксация активных задач](https://github.com/users/BorAlex7/projects/2/views/1)
![img](https://i.postimg.cc/8kFzL2GB/image.png)
### 1.2. Оценка трудозатрат
|Участник|Задача|Плановая|Фактическая
|--|--|--|--
|АД (Мастер) | Получает оценку времени для каждой подзадачи, собирает sprint log, назначает исполнителей | 120 мин | 90 мин
|АД (Мастер) | Проводит stand-up совещание | 60 мин | 60 мин
|АД (Мастер) | Проводит демонстрацию результатов спринта владельцу продукта и другим заинтересованным лицам | 60 мин | 
|БА (Тестировщик) | Разбивает задачу истории на подзадачи - тесты | 180 мин |  120 мин
|БА (Тестировщик) | Разрабатывает процедуры - тесты и тестовые наборы данных | 120 мин |  120 мин
|БА (Тестировщик) | Разрабатывает и отлаживает процедуры - тесты и тестовые наборы данных | 90 мин |  90 мин
|ВН (Дизайнер) | Разбивает эскиз интерфейса для приложения при отображении на экране устройства | 60 мин | 60 мин
|ВН (Дизайнер) | Разрабатывает дизайн интерфейса для приложения при отображении на экране устройства | 120 мин | 120 мин
|ВН (Дизайнер) | Разрабатывает прототип интерфейса для приложения при отображении на экране устройства | 120 мин | 120 мин 
|ВН (Дизайнер) | Разрабатывает и отлаживает процедуры - страницы, позволяющие выполнять тесты в интерактивном режиме | 90 мин | 90 мин 
|КО (Тех.писатель) | Создает техническую документацию для всех подзадач, требующих программной реализации | 120 мин |  120 мин
|КО (Тех.писатель) | Корректирует или делает новые описания для всех разработанных процедур | 60 мин |  60 мин
|КО (Тех.писатель) | Разрабатывает требуемые описания всех разработанных процедур, тестов и тестовых наборов данных | 60 мин |  60 мин
|НИ (Архитектор) | Разбивает задачу истории на подзадачи - процедуры | 60 мин | 60 мин
|НИ (Архитектор) | Определяет дополнительные требования к выполнению задач | 30 мин |  30 мин
|НИ (Архитектор) | Принимает решение по всем выявленных несоответствиям требованиям | 30 мин | 30 мин 
|ПП (Программист) | Разрабатывает алгоритмы выполнения всех подзадач, требующих программной реализации | 60 мин | 30 мин
|ПП (Программист) | Разрабатывает процедуры - обработчики и генераторы тестовых наборов данных | 180 мин |  120 мин
|ПП (Программист) | Разрабатывает и отлаживает процедуры - генераторы тестовых наборов данных | 120 мин |  100 мин
|РП (Владелец продукта) | Регистрирует участников проекта | 90 мин | 30 мин
|РП (Владелец продукта) | Принимает решение по всем возникающим проблемам | 60 мин |  60 мин
|РП (Владелец продукта) | Принимает решение об успешности спринта, дает общую оценку работы команды и дает предложения по всем индивидуальным оценкам | 60 мин |  60 мин
|СП (Аналитик) | Анализирует предметную область | 60 мин | 60 мин
|СП (Аналитик) | Регистрирует возникающие дополнительные задачи (issue) в соответствующих проектах | 60 мин | 60 мин
|СП (Аналитик) | Выполняет все разработанные тесты, регистрирует все выявленные несоответствия требованиям | 120 мин| 60 мин

## 2. Проектирование
### 2.1. Создание диаграммы IDEF0
![img](https://i.postimg.cc/NMqpphV9/2.png)
![img](https://imgur.com/6kiauOp.png)

### 2.2. Создание диаграммы UML Activity
![img](https://i.postimg.cc/zDpNy5VG/3.png)


### 2.3. Создание эскиза
![img](https://i.postimg.cc/HsvG3xtr/x-Dc-ORLOAHz-e-Hs-V1nj-PEk-UU26-Ewoj-Vigo-GQRVg-A0ue-Eq-X8l-CVfn-K-p-Aly76-Hd-Hd-ado-V2-W-8x3yz-U-5b-2uqtd-A.jpg)
![img](https://i.postimg.cc/KjQ66vSs/i-R30-qc-JWDH1-GCm9-BWy-ZMkio-PJRQo-Lktzd1-F4u-VJI-Zbzk-P7wp-Kb-CSf-ZNg5-XLwn-Sg-QSd-ISRlbx-Y0x-I4-MOQFAv-H.jpg)
![img](https://i.postimg.cc/ZKS0Zfk8/B3-Inx3j-L-Kjg-X2n-Je-Rbl-Uf-Wel-J6ma-T5-NEznm4-Tpy-Qw-Ig-Pfs-Q59-QFYq-CYp-M5-JJr-J6f-E8vf3bi0-S-8a-ZPnz3ycwf-G.jpg)
![img](https://i.postimg.cc/cJnNvSwr/Cp29im-Xvnz3c-EX62-Ebl-CHYc2s-Ovi-USBl-DGs-EEFwq9fh-769-KWe-Te-H-At-AJubiv-VTUs-Ii-Hdxj-Z6i-RR9t4-C3-L3j-MAd.jpg)

### 2.4. Описание продукта

#### Система:
* Хранит в себе данные о работниках и читателях (+ логины и пароли);
* Хранит в себе данные о книгах, их статусе и местонахождении;
* Хранит историю взятия и возвращения книг читателями.

#### Библиотекарь:
* Вводит в систему данные о новой книге/Списывает старые книги;
* Регистрирует в системе нового читателя (возможно нового работника библиотеки, но тогда это под отдельную роль);
* Регистрирует возвращение книги (статус книги: у библиотекаря);
* Может просматривать общую историю взятия книг;
* Вводит местоположение книги.

#### Читатель:
* Делает запрос на книгу;
* Получает данные о наличии книги;
* Фиксирует взятие книги и узнает её местонахождение;
* Видна информация взятия и возвращения книги (личный кабинет/история).

### 2.5. Формирование тестов
|Критерий|Прошел тест или нет
|--|--
|Зайти через логин и пароль читателя|✅ или ❌
|Выбрать книгу|✅ или ❌
|Получить данные о местоположении книги|✅ или ❌
|Зайти через логин и пароль билиотекаря|❌
|Отметить, что книга возвращена читетелем|❌
