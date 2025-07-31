---
tags:
  - now 
date: "2024"
cssclasses:
  - dropcaps
---
welcome to **Renaissance Scholar**, a theme crafted for the contemplative mind and the discerning eye. This design draws inspiration from the elegance of incunabula,[^1] the balance of classical [marginalia](https://en.wikipedia.org/wiki/Marginalia), and the quiet dignity of vellum and ink. Whether you annotate ancient texts, compose original treatises, or collect fragments of thought, this [[environment]] aspires to be more than a digital notebook: it is a *scriptorium* for the modern humanist. Let your words find structure, your insights light, and your scholarship rest within these pages. 
# h1 - Lorem Ipsum
## h2 - Lorem Ipsum
### h3- Lorem Ipsum
#### h4 - Lorem Ipsum
##### h5 - Lorem Ipsum
###### h6 - Lorem Ipsum

> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna [[aliqua]]. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit [[anim]] id est laborum.

Supported Ligatures and Special Characters:
- Æ æ | *Æ æ*
- Œ œ | *Œ œ*
-  ß | *ß*
-  ſ | *ſ*
### Block Quotes

>[!quote]
>This is a quote or reference callout.  

>[!question]  
>**Q**: What is the airspeed velocity of an unladen swallow?  

>[!info]
> Use `[!info]` for general information or factual notes.

>[!warning]
> Caution! Hazard ahead.

>[!tip]-
> Remember to check your references.

### Code Blocks & Code
`Here` is an example of a `line code box` within the text. *For a full list of the various languages, vid. [[Hello World|this note]]*.

```python
from x import y
if a == b:
	pass
else:
	run(a)
```

```shell
pip install numpy
```

### Tables
| Title                                             | A Title that Covers More than One Line                                                                                             |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| [Link](https://en.wikipedia.org/wiki/Lorem_ipsum) | [[Table\|Link to another note]]                                                                                                    |
| One line of text                                  | Example of a piece of text that spans multiple lines of the table, providing a [[full]] example of how the tables render the text. |
|                                                   |                                                                                                                                    |
|                                                   |                                                                                                                                    |
### Side Notes
Instead of highlighting, with this theme, you can easily make a side note==cf. 1Cor 5:18; Sam. 3:15; Mat. 7:21.==, using \=\=text\=\=. 

### Extra Modifications

#### Handwritten Text
You can easily create some blocks with cursive text using HTML.
<div class="handwriting">Handwritten text.</div>

```html
<div class="handwriting">Handwritten text</div>
```

If you want to avoid HTML, use {.handwriting} within the paragraph that you want to be handwritten, given that the Markdown Attributes plugin is installed. This modification is visible only in the Preview mode.
#### Marginalia
Marginalia are handwritten notes on the margin of the page, handwritten side notes.
<div class="right-marginalium">Marginalium example</div>

```html
<div class="right-marginalium">Marginalium example</div>
```

If you want to avoid HTML, use {.right-marginalium} within the paragraph that you want to be a marginalium, given that the Markdown Attributes plugin is installed. This modification is visible only in the Preview mode.

#### Glyph Separator
<span class="glyph-separator">✥</span>
```html
<div class="glyph-separator">✥</div>
```

___
#### Dropped Capital (Drop Cap)
There are two types of Dropped Capital:
1. By adding `dropcaps` in the `cssclasses` section of the `YAML`, you can have the first letter of the first paragraph of the note as a Drop Cap, in the font `Manufacturing Consent`.
2. Given that you have installed the Markdown Attribute plugin, you can add {.drop-cap-\[language and number]} at the end of the paragraph. The modification is visible only in Preview Mode (you must have the fonts installed on your computer, as they are not included in Google Fonts). The following fonts exist:
##### lat1 (latin One)
The 'Lat1' option matches the built-in drop cap function, as seen in `Manufacturing Consent`. It’s the only one that doesn't require installing any other font. This style evokes the clarity and structure of early printing houses, with a distinct blackletter touch that commands attention without overwhelming the page. Perfect for formal texts, manifestos, or academic introductions.  
{ .drop-cap-Lat1}

##### lat2 (Latin Two)
This second option displays the first letter in the highly decorated `Goudy Initialen` font. Inspired by Renaissance woodcut initials, it bursts with swirling foliage, floral motifs, and typographic grace. It works well in narrative texts, romantic essays, or any piece that deserves a touch of handcrafted nobility. You can install it for free from [here](https://www.1001fonts.com/goudy-initialen-font.html).  
{ .drop-cap-Lat2}

##### lat3 (Latin Three)
The third option offers a more minimal, yet still beautiful, dropped capital in the `CamelotCaps` font. With a Medieval simplicity and Arthurian elegance, it bridges the clean lines of modernity with the dignified tone of ancient romance. Ideal for storytelling, fables, or light academic prose. You can download it for free from [here](https://www.1001fonts.com/camelotcaps-font.html).  
{ .drop-cap-Lat3}

##### lat4 (Latin Four)

This fourth option uses the font `Cherubic Initials`, a highly ornamental and regal font created in 2005. It features decorative initials adorned with cherubs and floral patterns, reminiscent of Baroque and Rococo aesthetics, filtered through Victorian revival design. It is ideal for creating an embellished, ecclesiastical or fairy-tale feel. You can download it for free from [here](https://www.fontspace.com/cherubic-initials-font-f4678).  
{ .drop-cap-Lat4}



# Footnotes
[^1]: Footnote Example: *Lorem Ipsum*