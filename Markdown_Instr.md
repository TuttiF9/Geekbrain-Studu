## Markdown

## Абзацы
Чтобы создать абзацы, используйте пустую строку для разделения одной или нескольких строк текста.

## Заголовок
# Heading level 1
## Heading level 2
###### Heading level 6
 поставить # перед текстом. от 1 до 6. 1 большой, 6 маленький.

## Выделение текста

*Курсив* - добавить * до и после текста или слова.

**Полу-жирный** - добавить ** до и после текста или слова.

***Полу-жирный курсив*** - добавить *** до и после текста или слова

## Блоковые кавычки

Блоковые кавычки с несколькими абзацами

Блок-кавычки могут содержать несколько абзацев. Добавьте символ >в пустых строках между абзацами.

Вложеные цитаты - добавить >> в начале абзаца.
> Я использую Marckdown
>
>>И это классно!



## Списки

###### Неупорядоченные списки

* Первый 
* Второй
    - Второй с половинкой
    - Второй и три четверти
* Третий

В начале абзаца добавить * или + или -, для подпунктов добавить отступ 4 пробела или табуляцию.

###### Упорядоченные списки

1. Первый 
2. Второй
3. Третий

В начале абзаца добавить 1. 2. 3. и тд

###### Добавление элемента в список

- Первый
- Второй

    Что-то еще
- Третий

Чтобы добавить еще один элемент в список, сохраняя при этом непрерывность списка, сделайте отступ для элемента на четыре пробела или одну табуляцию.

## Код

    `iseedeadpeople`

Чтобы обозначить слово или фразу как код, заключите его в обратные кавычки ( `)


    Использую ` до и после ``iseedeadpeople`` что бы выделить в текте код

Если слово или фраза, которую вы хотите обозначить как код, включает одну или несколько обратных кавычек, вы можете экранировать их, заключив слово или фразу в двойные обратные кавычки ( ``)

    `Code`
        `Code`

Для создания блоков кода 4 пробела или 1 табуляция

## Ссылки

[www.gb.ru](www.gb.ru)

Чтобы создать ссылку, заключите текст ссылки в скобки [ ], а затем сразу же укажите URL-адрес в круглых скобках ( )

<fake@mail.net>

Почту заключить в угловые скобки < >

**[www.gb.ru](www.gb.ru)**

Чтобы добавить форматирование к ссылке, добавьте звездочки до и после квадратных скобок. Чтобы обозначить ссылки как код , добавьте обратные кавычки в скобки.

## Изображения

Чтобы добавить изображение, добавьте восклицательный знак ( !), за которым следует замещающий текст в скобках, а также путь или URL-адрес к ресурсу изображения в круглых скобках. При желании вы можете добавить заголовок в кавычках после пути или URL-адреса.

![Markdown-markdown-everwhere](https://media.makeameme.org/created/markdown-markdown-everywhere.jpg)

\![Markdown-markdown-everwhere](https://media.makeameme.org/created/markdown-markdown-everywhere.jpg)

## Экранирующий символ

Чтобы отобразить буквальный символ, который в противном случае использовался бы для форматирования текста в документе Markdown, добавьте \перед символом обратную косую черту как на примере выше.

Экранировать можно следующие символы

- \	обратная косая черта
- `	обратная кавычка 
- \*	звездочка
- _	нижнее подчеркивание
- { }	Фигурные скобки
- [ ]	кронштейны
- < >	угловые скобки
- ( )	круглые скобки
- \#	решетка
- \+	плюсик
- \-	знак минус (дефис)
- .	точка
- !	восклицательный знак
- |	прямая черта

## Таблицы

|Столбец 1|Столбец 2|Столбец 3|
|-|--------|---|
|Длинная запись в первом столбце|Запись в столбце 2|Запись в столбце 3|
|Кртк зпс| |Слева нет записи|

Столбцы разделяются вертикальными линиями |, а строка с шапкой отделяется от остальных дефисами -, которых можно ставить сколько угодно.

|Столбец 1|Столбец 2|Столбец 3|<br>
|-|--------|---|<br>
|Длинная запись в первом столбце|Запись в столбце 2|Запись в столбце 3|<br>
|Кртк зпс| |Слева нет записи|

|Столбец 1|Столбец 2|Столбец 3|
|:-|:-:|-:|
|Равнение по левому краю|Равнение по центру|Равнение по правому краю|
|Запись|Запись|Запись|

Чтобы выровнять весь столбец по правому краю, в строке с дефисами сразу после дефисов можно поставить двоеточие :. Чтобы выровнять содержимое по центру, надо поставить двоеточия с обеих сторон.

|Столбец 1|Столбец 2|Столбец 3|<br>
|:-|:-:|-:|<br>
|Равнение по левому краю|Равнение по центру|Равнение по правому краю|<br>
|Запись|Запись|Запись|

## HTML и Markdown

Многие приложения Markdown позволяют использовать теги HTML в тексте в формате Markdown. Это полезно, если вы предпочитаете определенные теги HTML синтаксису Markdown. Например, некоторым людям проще использовать HTML-теги для изображений. Использование HTML также полезно, когда вам нужно изменить атрибуты элемента, например указать цвет текста или изменить ширину изображения.

Чтобы использовать HTML, поместите теги в текст файла в формате Markdown.

<em style="color:#FF0000">Красный курсив</em>

\<em style="color:#FF0000">Красный курсив</em>

## Markdown и мессенджеры

Принципы Markdown используются при разметке текста во многих мессенджерах. Обычно он используется для выделения текста, при этом синтаксис у каждой платформы свой.

**Жирный**:

<span style="color:#F08080">Telegram и Discord</span> — * \*две звёздочки с двух сторон* *.

<span style="color:#F08080">WhatsApp и Viber</span> — \*одна звёздочка с двух сторон*.

*Курсив*:

<span style="color:#F08080">Telegram</span> — _ \_два нижних подчёркивания с двух сторон_ _;

<span style="color:#F08080">WhatsApp и Viber</span> — \_одно нижнее подчёркивание с двух сторон_;

<span style="color:#F08080">Discord</span> — \*одна звёздочка с двух сторон* или \_одно нижнее подчёркивание с двух сторон_.

<u>Подчёркнутый</u>:

<span style="color:#F08080">Discord </span>— _ \_два нижних подчёркивания с двух сторон_ _.

~~Зачёркнутый~~:

<span style="color:#F08080">WhatsApp и Viber</span> — ~одна тильда с двух сторон~;

<span style="color:#F08080">Discord</span> — \~~две тильды с двух сторон~~.

Моноширинный (используется для вставки кода):

<span style="color:#F08080">Telegram, WhatsApp, Viber и Discord</span> — \```три обратных апострофа с двух сторон```;
в Discord точно так же, как и в Markdown, можно указывать язык программирования для подсветки синтаксиса.

Спойлер:

<span style="color:#F08080">Telegram и Discord</span> — ||две вертикальные черты с двух сторон||.
