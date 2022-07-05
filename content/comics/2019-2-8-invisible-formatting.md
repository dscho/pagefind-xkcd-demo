---
date: 2019-02-08
title: "Invisible Formatting"
num: 2109
alt: >-
  To avoid errors like this, we render all text and pipe it through OCR before processing, fixing a handful of irregular bugs by burying them beneath a smooth, uniform layer of bugs.
img: https://imgs.xkcd.com/comics/invisible_formatting.png
---
[A text editor, with some options. They are superscript in one section, bold, italic and underscore in another section and alignments in the third section. The word "not ", including the following space, is highlighted in blue. There is a cursor below it.]

Text: ...ere, but would not have to mo...

Action: Select

[The cursor is on the "bold" option and the selected word is bolded.]

Text: ...ere, but would not have to mo...

Action: Click

[The cursor is next to the "to". No text is highlighted.]

Thought bubble: ...Nah, the bold is too much.

Text: ...ere, but would not have to mo...

[The word "not" is now highlighted in blue again, but the following space is not.]

Text: ...ere, but would not have to mo...

Action: Select

[The cursor is on the "bold" option and the selected word is not bolded.]

Text: ...ere, but would not have to mo...

Action: Click

[The cursor and the blue highlighting are gone. The space after "not" has a dashed box around it, and an arrow points to it.]

Text: ...ere, but would not have to mo...

Arrow: Hidden bold space

[Caption below the panels:]

When editing text, in the back of my mind I always worry that I'm adding invisible formatting that will somehow cause a problem in the distant future.