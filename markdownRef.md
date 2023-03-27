# Table of Contents

- [Table of Contents](#table-of-contents)
  - [Headings](#headings)
  - [Text Formating](#text-formating)
  - [Links](#links)
  - [Lists](#lists)
  - [Code Formatting](#code-formatting)
  - [Images](#images)
  - [Tables](#tables)
  - [Task Lists](#task-lists)
  - [Emojis](#emojis)
  - [Hidden Comments](#hidden-comments)
  - [Toggle](#toggle)
  - [Callout](#callout)
  - [Creating a Table of Contents \[TOC\]](#creating-a-table-of-contents-toc)

&nbsp;

## Headings

&nbsp;

# Headings 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

## &nbsp;

## Text Formating

**Note**: \* = italic, ** = bold, \*** = mix italic and bold

_italic text_ and _more italic text_

**bold text** and **more bold text**

**_bold and italic text_**

Hi! I'm **Alun** _Price_

~~Strikethrough Text~~

&nbsp;  
Paragraph text only starts a new line after 2 enters ..

Paragraph line spacing is
important (1 x enter)

**OR**

Paragraph line spacing is

important (2 x enter)

&nbsp;

## Links

[Google Link](https://google.com "Link to Google")

Note: "Link to Google" shows up as a tag on hovering the link

Linking to other links in the doc: just typing the # gives you the list of links on the doc - awesome!!!

[Links](#headings-1)

Ref Links : we can create ref links at the bottom of the doc using [ ] and refer to them - useful when you use the same link address often ...

[Google Ref Link][gl]

[gl]: https://google.com "Add this pop up title"

## Lists

Ordered List

1. Item 1
2. Item 2
3. Item 3

Unordered List

- Item 1
- Item 2
- Item 3

## Code Formatting

Inline: Use Javascript `map()` on arrays.

Fenced Code Blocks:

##### Javascript = ```js

```js
const sum = (a, b) => a + b;

sum(2, 2);
```

##### Python = ```py

```py
const sum = (a, b) => a + b

sum(2, 2)
```

##### Code Block : ``` no language

```
const sum = (a, b) => a + b

sum(2, 2)
```

BlockQuotes:

> This is a blockquote
>
> With multiple lines ....

## Images

![alt text goes here](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)

Turn the image into a link ... Wrap in [ ] and add the link in ( ) ...

[![alt text goes here](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)](https://developer.mozilla.org/en-US/docs/MDN/Writing_guidelines/Howto/Markdown_in_MDN "Link to MDN ref on How to Write in Markdown")

## Tables

| Packages |     Description      | Version |
| :------- | :------------------: | ------: |
| React    | JavaScript Framework |   v18.0 |
| Next.js  |   React Framework    |   v12.0 |

## Task Lists

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

Note: spacing is important of '-' and '[ ]' and x denotes task complete!

## Emojis

Emoji's are fun :joy:

## Hidden Comments

[this is a hidden comment that shows up in the markdown but not on the page!!]: #

## Toggle

<details>
    <summary> This is a TOGGLE!!!</summary>

    Contents of toggle!!

</details>

## Callout

This is just a stylized blockquote but useful ...

> :bulb: **Tip:** Here's an important tip to remember!!

## Creating a Table of Contents [TOC]

In VSCode, using the Markdown All in One, this is automated for you. Ctrl-Shift-P to open the Command Palette and search for Markdown All in One: Create Table of Contents. You may want to prune the tree created from the doc headings and move the TOC to the start of the document so you can use those useful links to quickly navigate..

Tip: turn off markdown.extension.toc.updateOnSave setting to allow you to remove headings that are not wanted but that get regenerated on save!!\*\*\*\*
