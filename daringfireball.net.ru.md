Это заголовок 1 уровня (тип Setext).
====================================

Это заголовок 2 уровня (тип Setext).
------------------------------------

###### Для заголовков типа atx используются символы `#` (1-6). Это уровень 6.
###### Заголовки типа atx можно выделять символами `#` с обеих сторон. ######
Количество закрывающих символов `#` в заголовке не имеет значения.

> Это цитата (blockquote).
> ### И заголовок уровня 3 (тип atx) внутри цитирования.
> Еще одна строка.
> Третья строка текста.
> > Цитирование также может быть вложенным.
> > Это делается добавлением дополнительных знаков `>`.
> > Как в этом предложении.

> Цитирование может также содержать другие элементы Markdown. Например, списки:

> 1. Первый элемент.
> 2. Второй эелемент.

> Или участки кода:

>     return shell_exec("echo $input | $markdown_script");


> При цитировании, можно выделять символом `>` только первую строку, как в этом параграфе. Хотя выделение каждой строки в исходном тексте Markdown выглядит лучше. This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.


Чтобы сделать простой перенос строки, нужно добавить два или более пробела в конце строки. Для создания нового параграфа нужно вставить пустую строку. Простой перенос строки в Markdown не учитывается и эта строка будет частью параграфа.

Некоторые слова здесь *выделены*.  
В этой строке они _тоже выделены_.

Для полужирного написания нужно использовать  **двойную звездочку**. Также, можно использовать __двойной знак подчеркивания__.

Это маркированный список. В таких списках можно использовать символы: `*`, `-`, `+`:

* Элемент списка
* Элемент списка
* Элемент списка
* Элемент списка
* Элемент списка


Это нумерованный список:

1. Один.
2. Два.
    -   Конфета.
    -   Жвачка.
    -   Пиво.
3. Три.

В нумерованных списках последовательность указанных в Markdown цифр не имеет значения. В HTML-форматированном выводе они будут отображаться корректно. Но начинать следует с цифры 1.

Можно оставлять отступы в списках. Так списки выглядят более красиво в тексте Markdown:

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.


*   Списки также могут содержать несколько параграфов.

    Это второй параграф в элементе списка. Параграф нужно выделить
отспутом (один и более Tab или 4 и более пробелов). Последующие строки
параграфа также можно выделять отступами, но это не обязательно.
Lorem ipsum dolor sit amet, consectetuer adipiscing elit.

*   Еще один элемент списка.


Это простой пример [ссылки](http://example.com/). Здесь еще одна [ссылка](http://example.com/ "С заголовком").

Можно также использовать ссылки со сносками, которые определяются в другом месте документа: "Мой трафик от [Google][1] превышает трафик от [Yahoo][2] or [MSN][3]".  
Заголовок ссылки не обязятелен. Имена ссылок могут содержать буквы, цифры и пробелы. Также они регистро-независимы:  
Я начинаю свое утро с чашки кофе и свежего номера [The New York Times][NY Times].

Так можно вставлять изображения:

![Эмблема хакеров](https://upload.wikimedia.org/wikipedia/commons/9/96/Animated_glider_emblem.gif)

В ссылках на изображение также можно использовать сноски:

![alt text][glider]

Выделять `участки текста как код` можно с помощью обратного апострофа, вот так `&mdash;`.  
А блоки текста нужно выделять отступами (один и более `Tab` или четыре и более `пробелов`):

                Это строка кода.
                Если вставить более одного Tab, это также будет код.
                                Текст также будет иметь соответствующий отступ.
                                В этом предложении отступы больше.

   А теперь тоже самое, только с пробелами (здесь их три).

    А здесь четыре.
    Еще одна строка.
      Текст с пробелами также будет иметь соответствующий отступ.

Markdown автоматически обрабатывает специальные символы HTML: `<` и `&`:  
&copy; - этот знак Markdown оставит как есть, т.е. в HTML он преобразуется в символ Copyright.  
Но если написать: AT&T, Markdown преобразует амперсанд в конструкцию `&amp;`:  AT&amp;T



[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"
[ny times]: http://www.nytimes.com/
[glider]: https://upload.wikimedia.org/wikipedia/commons/4/45/Glider.svg "Glider"