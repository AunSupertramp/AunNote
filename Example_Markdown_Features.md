# Example Markdown Features

This file demonstrates various Markdown features and syntax.

## Headers

# H1: Main Document Title
## H2: Section Heading
### H3: Subsection Heading
#### H4: Deeper Heading
##### H5: Even Deeper Heading
###### H6: Smallest Heading

## Emphasis

*This text is italic using asterisks.*
_This text is italic using underscores._

**This text is bold using asterisks.**
__This text is bold using underscores.__

***This text is bold and italic using asterisks.***
___This text is bold and italic using underscores.___

## Lists

### Unordered List

*   Item 1
*   Item 2
    -   Nested Item 2.1
    -   Nested Item 2.2
        +   Deeply Nested Item 2.2.1
*   Item 3

### Ordered List

1.  First item
2.  Second item
    1.  Nested ordered item A
    2.  Nested ordered item B
3.  Third item

### Task List

-   [x] Completed Task
-   [ ] Pending Task 1
-   [ ] Pending Task 2
    -   [x] Sub-task completed
    -   [ ] Sub-task pending

## Links

Here's an [example of an inline link](https://www.example.com "Example Website").

This is a [reference-style link][google-link].

[google-link]: https://www.google.com "Google Search Engine"

## Images

Here's an inline image:

![Placeholder Image](https://via.placeholder.com/150 "A simple placeholder")

And a reference-style image:

![Another Placeholder][placeholder-ref]

[placeholder-ref]: https://via.placeholder.com/100/FF0000/FFFFFF?text=Red+Box "Red Placeholder"

## Code

### Inline Code

To print something in Python, you use `print()`. For example, `print("Hello, World!")`.

### Code Blocks

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

print(factorial(5))
```

```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}

greet("Markdown");
```

## Blockquotes

> This is a simple blockquote.
> It can span multiple lines.

> This is a blockquote with multiple paragraphs.
>
> > This is a nested blockquote.
> > It's quite common to see these.
>
> Back to the first level of quoting.

## Horizontal Rule

---

***

___

## Tables

| Header 1 | Header 2 | Header 3 |
|:--------|:-------:|--------:|
| Left-aligned | Centered | Right-aligned |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |
| A short row | Another cell | Last cell |

## Strikethrough

This text is ~~struck through~~.

## Escaping Characters

To show a literal asterisk, use `\*`.

This is not italic: \*not italic\*

## Automatic Links

Sometimes URLs are automatically linked: <https://www.example.com>

## Backslash Escapes

Markdown allows you to use a backslash to escape any character that would otherwise be interpreted as Markdown formatting.

For example, if you want to write `*literal asterisks*` without them being interpreted as italics, you would write `\*literal asterisks\*`.

