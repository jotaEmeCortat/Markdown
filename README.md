# **Menu**

- [Headings](#headings)
- [Paragraphs](#paragraphs)
- [Emphasis](#emphasis)
- [Blockquotes](#blockquotes)
- [Lists](#lists)
- [Images](#images)
- [Code](#code)
- [Links](#links)
- [Escaping Characters](#escaping-characters)
- [Tables](#tables)
- [Task Lists](#task-lists)
- [Horizontal Rules](#horizontal-rules)
- [Space](#space)

---

&nbsp;

## **Headings**

```markdown
# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6
```

### **Linking to Heading IDs**

You can link to headings with custom IDs in the file by creating a standard link with a number sign (#) followed by the custom heading ID.

```markdown
# This is my Header

[link](#this-is-my-header)
```

> ### This is my Header
>
> [link](#this-is-my-header)

---

&nbsp;

## **Paragraphs**

To create paragraphs, use a blank line to separate one or more lines of text. You should not indent paragraphs with spaces or tabs.

```markdown
I really like using Markdown.

I think I'll use it from now on.
```

> I really like using Markdown.
>
> I think I'll use it from now on.

&nbsp;

### **Line Breaks**

```markdown
This is the first line.</br>And this is the second line.
```

> This is the first line. </br> And this is the second line.

---

&nbsp;

## **Emphasis**

### **Bold**

```markdown
I love **bold text**.
```

> I love **bold text**.

&nbsp;

### **Italic**

```markdown
The _cat's meow_.
```

> The _cat's meow_.

&nbsp;

### **Bold and Italic**

```markdown
**_Important_** text.
```

> **_Important_** text.

&nbsp;

### **Strikethrough**

```markdown
The world is ~~flat~~ round.
```

> The world is ~~flat~~ round.

---

&nbsp;

## **Blockquotes**

```markdown
> Dorothy followed her through many rooms.
```
> Dorothy followed her through many rooms.

&nbsp;

### **Blockquotes with Multiple Paragraphs**

> This the first paragraph.
>
> And this is the second paragraph.

&nbsp;

### **Nested Blockquotes**

> This the first paragraph.
>
> > And this is the nested paragraph.

&nbsp;

### **Blockquotes with Other Elements**

> ##### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> _Everything_ is going **well**.

---

&nbsp;

## **Lists**

### **Ordered Lists**

```markdown
1. First item
2. Second item
3. Third item
4. Fourth item
```

> 1.  First item
> 2.  Second item
> 3.  Third item
> 4.  Fourth item

&nbsp;

### **Nesting List Items**

```markdown
1. First item
2. Second item
3. Third item
   1. Indented item
   2. Indented item
4. Fourth item
```

> 1.  First item
> 2.  Second item
> 3.  Third item
>     1. Indented item
>     2. Indented item
> 4.  Fourth item

&nbsp;

### **Unordered Lists**

To create an unordered list, add _dashes (-)_, _asterisks (\*)_, or _plus signs (+)_ in front of
line items.

```markdown
- First item

* Second item

- Third item

* Fourth item
```

> - First item
>
> * Second item
>
> - Third item
>
> * Fourth item

&nbsp;

### **Nesting List Items**

To nest line items in an unordered list, indent the items four spaces or one tab.

```markdown
- First item
- Second item
  - Indented item
  - Indented item
```

> - First item
> - Second item
>   - Indented item
>   - Indented item

---

&nbsp;

## **Images**

You can optionally add a title after the URL in the parentheses.
```markdown
![markdown](https://geekytheory.com/content/images/2014/03/markdown_inte-1024x630.png 'markdown logo')
```
![markdown](https://geekytheory.com/content/images/2014/03/markdown_inte-512x315.png 'markdown logo')
---

&nbsp;

## **Code**

To denote a word or phrase as code, enclose it in tick marks (`).

```markdown
At the command prompt, type `nano`.
```

> At the command prompt, type `nano`.

&nbsp;

### **Code Blocks**

To create code blocks, indent every line of the block by at least four spaces or one tab.

```markdown
    <html>
        <head>
        </head>
    </html>
```

&nbsp;

### **Fenced Code Blocks**

Depending on your Markdown processor or editor, you’ll use three tick marks (```) or three tildes (∼∼∼) on the lines before and after the code block. The best part? You don’t have to indent any lines!

To add syntax highlighting, specify a language next to the tick marks before the fenced code block.

````markdown
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
````

> ```json
> {
>   "firstName": "John",
>   "lastName": "Smith",
>   "age": 25
> }
> ```

---

&nbsp;

## **Links**

```markdown
Use [Duck Duck Go](https://duckduckgo.com).
```

> Use [Duck Duck Go](https://duckduckgo.com).

&nbsp;

## **Anchor**
```markdown
Use [Duck Duck Go](https://duckduckgo.com).
```
> Use [Headings](#headings)

### **Automatic URL Linking**

```markdown
http://example.com
```

> http://example.com

&nbsp;

### **Disabling Automatic URL Linking**

If you don’t want a URL to be automatically linked, you can remove the link by denoting the URL as code with tick marks.

```markdown
`http://www.example.com`
```

> `http://www.example.com`

&nbsp;

### **Adding Titles**

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.

```markdown
Use [Duck Duck Go](https://duckduckgo.com 'My search engine!').
```

> Use [Duck Duck Go](https://duckduckgo.com 'My search engine!').

&nbsp;

### **URLs and Email Addresses**

To quickly turn a URL or email address into a link, enclose it in angle brackets.

```markdown
<https://eff.org>
<fake@example.com>
```

> <https://eff.org>
>
> <fake@example.com>

&nbsp;

### **Formatting Links**

To emphasize links, add asterisks before and after the brackets and parentheses.

```markdown
I love supporting **[EFF](https://eff.org)**.

This is the _[EFF](https://eff.org)_.
```

> I love supporting **[EFF](https://eff.org)**.
>
> This is the _[EFF](https://eff.org)_.

---

&nbsp;

## **Escaping Characters**

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash ( \ ) in front of the character.

```markdown
\* Without the backslash, this would be a bullet in an.
```

> \* Without the backslash, this would be a bullet in an.

#### **Characters You Can Escape**

You can use a backslash to escape the following characters.

- \\ backslash
- \` tick mark (see also escaping tick marks in code)
- \* asterisk
- \_ underscore
- \{ } curly braces
- \[ ] brackets
- \( ) parentheses
- \# pound sign
- \+ plus sign
- \- minus sign (hyphen)
- \. dot
- \! exclamation mark
- \| pipe (see also escaping pipe in tables)

---

&nbsp;

## **Tables**

To add a table, use three or more hyphens (---) to create each column’s header, and use pipes ( | ) to separate each column.

You can optionally add pipes on either end of the table.

```markdown
| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |
```

> | Syntax    | Description |
> | --------- | ----------- |
> | Header    | Title       |
> | Paragraph | Text        |

_Creating tables with hyphens and pipes can be tedious. To speed up the process, try using the [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables)._

&nbsp;

### **Alignment**

You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.

```markdown
| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |
```

> | Syntax    | Description |   Test Text |
> | :-------- | :---------: | ----------: |
> | Header    |    Title    | Here's this |
> | Paragraph |    Text     |    And more |

&nbsp;

### **Formatting Text in Tables**

You can format the text within tables. For example, you can add links, code (words or phrases in tick marks (` ) only, not code blocks), and emphasis.

You can’t add headings, blockquotes, lists, horizontal rules, images, or HTML tags.

&nbsp;

### **Escaping Pipe Characters in Tables**

You can display a pipe ( | ) character in a table by using its HTML character code ( &#124; ).

---

&nbsp;

## **Task Lists**

Task lists allow you to create a list of items with checkboxes.

To create a task list, add dashes ( - ) and brackets with a space ( [ ] ) in front of task list items. To select a checkbox, add an x in between the brackets ( [x] ).

```markdown
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

> - [x] Write the press release
> - [ ] Update the website
> - [ ] Contact the media

---

&nbsp;

## **Horizontal Rules**

To create a horizontal rule, use three or more asterisks (\*\*\*), dashes (---), or underscores (\_\_\_) on a line by themselves.

---
&nbsp;

## **Space**

```markdown
&nbsp;
```
---
