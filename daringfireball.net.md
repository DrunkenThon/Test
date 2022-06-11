This is a level 1 header.
=========================

One more level 2 header.
------------------------

> This is a blockquote.
> ### And a header (level 3) inside.
> And one more line.
> The third line of text.

Some of these words *are emphasized*.
Some of these words _are emphasized also_.

Use two asterisks for **strong emphasis**.
Or, if you prefer, __use two underscores instead__.

* Candy
* Gum
* Booze
* Four
* Five


Here is a numbered list:

1. One
2. Two
    -   Candy.
    -   Gum.
    -   Booze.
3. Three

This is an [example link](http://example.com/). And one more link [example link](http://example.com/ "With a Title").

Reference-style links allow you to refer to your links by names, which you define elsewhere in your document:

I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

The title attribute is optional. Link names may contain letters, numbers and spaces, but are not case sensitive:

I start my morning with a cup of coffee and [The New York Times][NY Times].

Image:

![Hacker Emblem](https://upload.wikimedia.org/wikipedia/commons/9/96/Animated_glider_emblem.gif)

Reference-style:

![alt text][glider]


Here are some examples of code spans.

I strongly recommend against using any `<blink>` tags.

I wish SmartyPants used named entities like `&mdash;`
instead of decimal-encoded entites like `&#8212;`.

Looks like we should indent the lines with tabs for the block:

                This should be the code.
                So if we indent the line by one or more tabs, it will be the code no matter what. There are pros and cons about that.
                                If we put more tabs, it is still the code block.
                                And the text is still indented accordingly.

   Now let's try the same with spaces (here are three).

    And now here are four.
    One more line.

to write about ‘AT&T’, you need 

[Link1](http://images.google.com/images?num=30&q=larry+bird)

[Link2](http://images.google.com/images?num=30&amp;q=larry+bird)


&copy; Markdown will leave it alone.

But if you write: AT&T

Markdown will translate it to:

AT&amp;T



[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"
[ny times]: http://www.nytimes.com/
[glider]: https://upload.wikimedia.org/wikipedia/commons/4/45/Glider.svg "Glider"
