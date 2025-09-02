# Markdown for Everyday Notes

## Introduction

### What is Markdown?

Markdown is a lightweight markup language, used to create formatted text. It was created in 2004, and was inspired by conventions used to format plain text in emails and online.

### Why Developers Use It

Since it was created, it has gained a place in the workflow of many developers, due to its simplicity and compatibility. Over the years, it has been extended and branched into different variants (or 'flavours') that offer more syntax options, allowing it to cater to different use cases.

### Why Non-Technical Users Can Use It Too

But Markdown isn’t just for developers. It’s extremely useful for taking quick notes when a rich editor (like Word, Notion, or Evernote) isn’t available. You can write Markdown in any plain text editor, read it as-is, or open it in a Markdown reader that will display the formatting in a clean, styled way.

---

## Core Features of Markdown

Below are the most common elements you’ll use in everyday writing.

---

### Headings

Use `#` symbols to define headings. The number of `#` indicates the level.

```markdown
# Heading 1

## Heading 2

### Heading 3
```

Rendered:

# Heading 1

## Heading 2

### Heading 3

---

### Emphasis

```markdown
_italic_  
**bold**  
~~strikethrough~~
```

Rendered:

_italic_  
**bold**  
~~strikethrough~~

---

### Lists

#### Unordered lists

```markdown
- Item one
- Item two
- Item three
```

Rendered:

- Item one
- Item two
- Item three

#### Ordered lists

```markdown
1. First
2. Second
3. Third
```

Rendered:

1. First
2. Second
3. Third

#### Task Lists (Checklists)

Task lists let you add checkboxes to your notes.  
⚠️ **Note:** Not all Markdown renderers support this feature (it works on GitHub, Obsidian, and many modern editors, but not in plain text).

```markdown
- [x] Write first draft
- [x] Revise content
- [ ] Publish final version
```

Rendered:

- [x] Write first draft
- [x] Revise content
- [ ] Publish final version

---

### Links and Images

Links and images use a similar structure in Markdown:

- **Links** → `[Link text](URL)`
- **Images** → `![Alt text](Image URL)`

The key difference is the **exclamation mark `!`** in front of the image syntax.

```markdown
[Visit OpenAI](https://openai.com)
```

Rendered:

[Visit OpenAI](https://openai.com)

```markdown
![Placeholder image](https://placehold.co/600x400)
```

Rendered:

![Placeholder image](https://placehold.co/600x400)

### Code

Markdown supports inline code and fenced code blocks.

**Inline code** is wrapped in single backticks:

<!-- Formatted with nested ticks to render correctly -->

````markdown
```
Use the `print()` function.
```
````

Rendered:

```markdown
Use the `print()` function.
```

---

### Blockquotes

Blockquotes are used to highlight quoted text or important information.  
They are created with the `>` symbol at the beginning of a line.

```markdown
> This is a blockquote.
>
> It can span multiple lines
```

Rendered:

> This is a blockquote.
>
> It can span multiple lines.

---

### Tables

Tables let you display structured data in rows and columns.  
They use pipes `|` to separate columns and hyphens `-` to define headers.

```markdown
| Name  | Role      | Location |
| ----- | --------- | -------- |
| Alice | Developer | Remote   |
| Bob   | Designer  | New York |
```

Rendered:

| Name  | Role      | Location |
| ----- | --------- | -------- |
| Alice | Developer | Remote   |
| Bob   | Designer  | New York |

---

### Horizontal Rule

Horizontal rules are used to create a visual break between sections. You can create them with hyphens, asterisks, or underscores.

<!-- prettier-ignore-start -->
```markdown
---
***
___
```

Rendered:

---
***
___
<!-- prettier-ignore-end -->

⚠️ Note: While horizontal rules can also be written with asterisksor underscores, some editors or formatters (like Prettier) may standardize them to hyphens.

---

## Conclusion

Markdown is simple, flexible, and widely supported.  
Whether you’re a developer documenting code, a student taking notes, or just someone who wants a distraction-free way to write, Markdown offers a lightweight solution that works almost anywhere.

It's easy to learn, yet powerful enough to handle everything from quick lists to full technical documents.
Best of all, you can always read the raw text as-is, or open it in a Markdown viewer to see it neatly formatted.

If you’re looking for a tool that balances clarity, portability, and ease of use, Markdown is a great place to start.
