# Markdown basics

Markdown is a lightweight markup language with plain-text syntax.
This document presents some basic Markdown syntax. 
If you're new to Markdown, or need to refresh your memory, this is a good place to start.

This document contains the following sections:

- [Basic formatting](#basic-formatting)
- [Headings](#headings)
- [Links](#links)
- [Code](#code)
- [Lists](#lists)
- [Tables](#tables)
- [Comments](#comments)
- [Images](#images)

## Basic formatting

Markdown lets you add some basic formatting to your text. For example, you can format text as **bold** or *italicized*. 

- To format text as **bold**, add two asterisks (`**`) before and after the text:
    
  ```
  **This text is bold.**
  ```

- To use *italics*, add one asterisk (`*`) before and after the text:

  ```
  This text is italicized.
  ```
  
###### [🔝 Go back up](#markdown-basics)
  
## Headings

To better structure your documents and improve readability, Markdown lets you use headings.
For example, the title of this document uses Heading 1 (H1), and the titles of the sections use Heading 2 (H2). There are six heading levels (H1-H6), with H1 being the biggest and H6 the smallest.
To add a heading, precede it with corresponding number of hashes (`#`) and one space.

- To format text as H1, use one hash (`#`) followed by a space before the text:

  ```
  # This is H1.
  ```
  
- To format text as H5, use five hashes (`#####`) followed by a space before the text:

  ```
  ##### This is H5.
  ```
  
> **NOTE:** Do not forget the space character after the hash(es)! Otherwise, the formatting won't work, and your text will be displayed as regular text preceded by a hash.

###### [🔝 Go back up](#markdown-basics)

## Links

Markdown lets you easily add hyperlinks to text.

- To add a hyperlink (like [this link to Google](https://google.com)) to a piece of regular text, enclose the linked text in the square brackets (`[]`), and follow it immediately with the target URL enclosed in parentheses (`()`):

  ```
  [This text links to Google](https://google.com)
  ```
  
  > **TIP:** If you don't want to provide alternative text to your link, just provide the URL without any additional formatting: `https://google.com`. This link will be highlighted and clickable. 

###### [🔝 Go back up](#markdown-basics)

## Code

To format a piece of text as code, you have two options: inline code and code blocks.

- To go with inline code formatting, use single backticks (`` ` ``).

  ```
  `This will be formatted as inline code.` 
  ```
  
  Inline code formatting looks like this: `inline code`.
  
- To go with a code block, use three backticks before and after the code.

  ``````
  ```This will be formatted as a code block.```
  ``````
  
  Code blocks look like this:
  ```
  Code block
  ```
  
###### [🔝 Go back up](#markdown-basics)

## Lists

Markdown has two types of lists: ordered and unordered.

- To use an ordered list, simply number your list elements, like this: 

  ```
  The elements of an ordered list are numbered:
  1. First list element
  2. Second list element
  3. Third list element
  ```
  
- To use an unordered list, use either hyphens (`-`) or asterisks (`*`), like this:

  ```
  The elements of an unordered list are not numbered:
  - A list element
  - Another list element
  - Yet another list element
  ```
  
  ```
  These unordered list elements start with an asterisk:
  * A new list element
  * Another new list element
  * Yet another new list element
  ```
  
  Regardless of which character you use, they are both rendered the same way. 
  
###### [🔝 Go back up](#markdown-basics)

## Tables

Markdown lets you organize text in tables, like this one:

| Column A | Column B, centered | Column C, aligned right | Column D, aligned left |
|----------|:------------------:|------------------------:|:-----------------------|
| Value A1 | Value B1           | Value C1                | Value D1               |
| Value A2 | Value B2           | Value C2                | Value D2               |

To create such a table, use the vertical bar (`|`) to separate columns, and hyphens (`-`) to separate rows, like this:
```
| Column A | Column B, centered | Column C, aligned right | Column D, aligned left |
|----------|:------------------:|------------------------:|:-----------------------|
| Value A1 | Value B1           | Value C1                | Value D1               |
| Value A2 | Value B2           | Value C2                | Value D2               |
```

The first row contains the table header, the second row separates the header from the actual content, the third and subsequent rows are the content.

> **TIP:** Note how you can use the colon (`:`) in the second row to align content in a given column. Place it on the right-hand side, left-hand side, or on both sides of the cell to align the content in the whole column along the left, right, or center it, respectively.

###### [🔝 Go back up](#markdown-basics)

## Comments

Although Markdown doesn't have a standard syntax for comments, there is an HTML-like solution that works for GitHub and many other platforms. It uses HTML-like tags: `<!--`, `-->`.  Comments are useful, because you might want to include a comment that will not show in the rendered document, but will show up in the raw version of the file. 
For example, you might want to write instructions on how to fill in a document template.
To add a comment, use the tags like this:

```
<!-- PLACE YOUR COMMENT HERE -->
```

<!-- See? You can't see this when it's rendered! -->

> **NOTE:** These tags are not the same, as the HTML comment tags. These have 2 hyphens (`-`), while the HTML tags have 3.

###### [🔝 Go back up](#markdown-basics)

## Images                                  

TODO

###### [🔝 Go back up](#markdown-basics)