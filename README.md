# Chat-bot

Чат-бот-це програма, яка імітує справжню розмову з користувачем. за допомогою якої можливо здійснювати комунікацію в аудіо- або текстовому форматі. Чат-бот використовують для виконання конкретних завдань (наприклад, отримання довідкової інформації, виконання розрахунків) або задля розваги.Програма імітує інтерактивну розмову людини за допомогою ключових, заздалегідь розрахованих фраз користувача, та слухових або текстових сигналів.

Мета даної роботи - створити програму яка б імітувала розмову з людиною та використовувалася з метою надання даних про знаходження того чи іншого магазина, чи приміщення в торговому центрі

Програма буде написана на мові програмування java та буде складатися з двух чистин або класів,а саме:

1)SimpleChatBot-графічна частина програми.В цій частині програми ми просто створемо саме вікно програми та задамо його розміри,після чого додамо но нього елементи керуванням програми,такі як кнопки,поля ітд.А в кінці додамо actionPerformed для того щоб інша частина програми змогла зрозуміти,що ми ввели та в результаті дати відповідь.

2)SimpleBot-програмна частина.Головним завданням програми є відповідь на запитання чи надання довідкових даних,проте не всі слова бот може розрізнити,тому бот буде відповідати загальними фразами,за це відповідають масиви QWITHOUTQM та QWITHQM.

Для того,щоб бот мав “розум” слід додати хешмеп PATTERNS_FOR_ANALYSIS розшифрувати можна як шаблони для аналізу,наприклад ми ведемо put("привіт", "hello").Ліва частина це те що водить користувач,права те що розуміє бот,тобто ключ,для правої створимо ще один хешмеп ANSWERS_BY_PATTERNS або відповіді за шаблоном за яким він буде орієнтуватися,що саме від нього хочуть.Хешмепів для того щоб розмовляти з ботом можна додати безліч,тим самим роблячи його більш досконалим.
