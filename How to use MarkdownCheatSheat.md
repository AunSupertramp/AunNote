# Markdown Cheat Sheet

This cheat sheet provides a quick reference for common Markdown syntax.

## Headers

Headers are used to structure your document. There are two ways to create headers:

### Atx-style Headers

Use 1 to 6 hash symbols (`#`) at the beginning of a line. The number of hashes corresponds to the header level.

```
# H1 - Main Title
## H2 - Section Title
### H3 - Subsection Title
#### H4 - Sub-subsection Title
##### H5 - Smallest Header
###### H6 - Even Smaller Header
```

## Emphasis

Emphasis is used to highlight text.

### Italic

Use single asterisks (`*`) or underscores (`_`) around the text.

```
*This text will be italic.*
_This text will also be italic._
```

### Bold

Use double asterisks (`**`) or double underscores (`__`) around the text.

```
**This text will be bold.**
__This text will also be bold.__
```

### Bold and Italic

Combine single and double asterisks/underscores.

```
***This text will be bold and italic.***
___This text will also be bold and italic.___
```

## Lists

Markdown supports ordered and unordered lists.

### Unordered Lists

Use asterisks (`*`), hyphens (`-`), or plus signs (`+`) followed by a space.

```
* Item 1
* Item 2
  - Nested Item 2.1
  - Nested Item 2.2
    + Deeply Nested Item 2.2.1
* Item 3
```

### Ordered Lists

Use numbers followed by a period (`.`) and a space. The actual numbers don't matter for rendering, but it's good practice to start with `1.`.

```
1. First item
2. Second item
   1. Nested ordered item
   2. Another nested item
3. Third item
```

### Task Lists (GitHub Flavored Markdown)

Create checkboxes in your lists.

```
- [x] Task 1 (completed)
- [ ] Task 2 (pending)
- [ ] Task 3
```

## Links

Create hyperlinks to other pages or resources.

### Inline Link

```
[Link Text](https://www.example.com "Optional Title")
```

### Reference-style Link

```
[Link Text][id]

[id]: https://www.example.com/ "Optional Title"
```

## Images

Embed images in your document.

### Inline Image

```
![Alt Text for Image](image.jpg "Optional Title")
```

### Reference-style Image

```
![Alt Text for Image][image-id]

[image-id]: /path/to/image.png "Optional Title"
```

## Code

Display code snippets.

### Inline Code

Enclose code within backticks (`` ` ``).

```
Use `console.log()` to debug.
```

### Code Blocks

Use triple backticks (````` ``` ````) before and after the code block. You can specify the language for syntax highlighting.

````
```python
def hello_world():
    print("Hello, World!")
```

```javascript
const message = "Hello, JavaScript!";
console.log(message);
```
````

## Blockquotes

Quote blocks of text.

```
> This is a blockquote.
> It can span multiple lines.
>
> > Nested blockquote.
>
> Back to the first level.
```

## Horizontal Rule

Create a thematic break. Use three or more hyphens (`-`), asterisks (`*`), or underscores (`_`) on a line by themselves.

```
---

***

___
```

## Tables (GitHub Flavored Markdown)

Create tables using hyphens and pipes (`|`).

```
| Header 1 | Header 2 | Header 3 |
|----------|:--------:|---------:|
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |
```

-   `:----------` for left-aligned column
-   `:--------:` for center-aligned column
-   `---------:` for right-aligned column

## Strikethrough (GitHub Flavored Markdown)

Use double tildes (`~~`) around the text.

```
~~This text will be struck through.~~
```

## Escaping Characters

To display a Markdown special character literally, precede it with a backslash (`\`).

```
\* This is not italic \*
```
