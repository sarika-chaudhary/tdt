---
title: Beginners' guide to Markdown
date: 2024-10-22
tags:
  - tutorial
  - markdown
featuredImage: /blogs/beginners-guide-to-markdown/md.jpg
---

## What is Markdown?
Nope. Markdown is not a programming language. It's rather a markup language i.e. a language that allows you to format your text. What's special about markdown is that it allows you to format your text by just using (some more) text.
For example, you must have wrapped your text in `*` or `_` to make it bold or italic while sending a text message on WhatsApp. That's similar to markdown syntax (not exactly markdown though) formatting your text i.e. making it bold or italic using plain text (`*` or `_`).
It was created in 2004 by a tech blogger named John Gruber.

## Why learn markdown?
Because it's easy and you can use it almost anywhere. All you have to do is remember a few syntax. It's like "neat handwriting" for the digital world, except you don't need fancy pens and markers and highlighters for writing a well-organised note.
It's like doing a basic maths calculation to know much you are going to pay for two packs of chips and a bottle of coke at the rate of Rs 10 and Rs 30 respectively (Answer is Rs 50 😎). Once you get hang of it, it's as intuitive and as universal, I would argue.
You can use markdown syntax in [Discord](https://discord.com/), [Slack](https://slack.com/), [Google Docs](https://docs.google.com/), [Github](github.com), [R Studio](https://posit.co/products/open-source/rstudio/), and the list goes on. In fact, you can make yourself a website in markdown using static site generators like [Hugo](https://gohugo.io/) and [Jekyll](https://jekyllrb.com/).

## Basic Markdown Syntax
### Headings
To make a heading, put some `#` in front of your text

`#` Heading 1 (i.e. the largest heading) <br>
`##` Heading 2 <br>
`###` Heading 3 <br>
`####` Heading 4 <br>
`#####` Heading 5 <br>
`#####` Heading 6 (i.e. the smallest heading)

### Lists
#### Unordered list
Put `*` or `-` followed by space and *some text* to convert the *some text* into an unordered list i.e. add a bullet point before it.
- Item 1
- Item 2
- Item 3

#### Ordered list
Put `1.` or `2.` etc. followed by space and *some text* to convert it into an ordered list i.e. add list number before it. 
1. Item 1
2. Item 2
3. Item 3

### Blockquote
Put `>` followed by space and *some text* to convert it into an blockquote.
> This is blockquote.

### Inline text formatting
Wrap your text in `*` or `_` to convert it into *italic* text. <br>
Wrap your text in `**` or `__` to convert it into **bold** text.  <br>
Wrap your text in `***` or `___` to convert it into ***bold & italic*** text. <br>
Wrap you text in `` ` `` to convert it into an inline `code`. <br>
Wrap your text in `~~` to convert it into ~~strikethrough~~ text.

### Links
To create a link, put the link text inside `[]` followed by its url inside `()` <br>
e.g. `[Tiny Data Tales](https://www.tinydatatales.com)` → [Tiny Data Tales](https://www.tinydatatales.com)

### Image
To insert an image, put the image alt text inside `![]` followed by path or url of the image inside `()` <br>
e.g. `![Wikipedia logo](https://upload.wikimedia.org/wikipedia/commons/d/d1/Wikipedia_logo_v2_en_on_white_background.svg)` → ![Wikipedia logo](https://upload.wikimedia.org/wikipedia/commons/d/d1/Wikipedia_logo_v2_en_on_white_background.svg)

### Horizontal rule
To create a horizontal rule or divider, put three or more `***` or `---` or `___`

----

### Side note
Just for the record, here's WhatsApp's formatting syntax. (While it's not exactly markdown, it is inspired by markdown. Just another example of tech-giant flouting the rules in their favour)

Italic : `_text_` <br>
Bold : `*text*` <br>
Strikethrough : `~text~` <br>
Monospace : `` ```text``` `` <br>
Quote: `> text` <br>
Inline code : `` `text` `` <br>
Bulleted list : <br>
`* text` <br>
`* text`  <br>
Numbered list : <br>
`1. text` <br>
`2. text` <br>


### See also
- [dillinger.io](https://dillinger.io/), an excellent online markdown editor to write and preview markdown files
- Original [post](https://daringfireball.net/projects/markdown/) of John Gruber introducing markdown. 
- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/) (stick with basic syntax or learn additional syntax when you feel ready)
- [Github flavoured markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) adds additional syntax for making documentation on Github more robust

- Read another tech blogger taking a dig at WhatsApp (and others) for not conforming to the markdown syntax: [WhatsApp and Markdown-ish?](https://blog.pesky.moe/posts/2023-09-18-markdown-chat/)
