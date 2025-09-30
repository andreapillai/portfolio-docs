# GitHub Flavored Markdown

## Introduction

GitHub Flavored Markdown (GFM) is a variant of **Markdown** that extends the basic syntax, adding extra features that are specifically useful for software development.
It builds upon standard Markdown by adding features such as checkboxes, mentions, and tables.

## GFM-Specific Syntax

### Task Lists (Checkboxes)

Task lists let you create checkboxes. This is especially useful for tracking to-dos in issues or documentation. To create one, start a list item with a hyphen, a space, and [ ] for an empty box or [x] for a checked box.

⚠️ Note: Not all Markdown platforms support task lists. This syntax will work on GitHub (and many modern editors like Obsidian), but in a plain text context you’ll just see the literal [ ] and [x].

```
- [x] Write unit tests
- [ ] Fix bugs
- [ ] Update documentation
```

Rendered:

- [x] Write unit tests
- [ ] Fix bugs
- [ ] Update documentation

(On GitHub, and viewers that support this syntax, the brackets turn into actual checkboxes. In issues and pull requests, you can even click them to toggle the status.)

### Tables (with Column Alignment)

Standard Markdown didn't originally support tables, but GFM allows you to create them using pipes `|` and hyphens `-`. You can also **align** text inside columns by adding colons `:` in the header separator line:

- :--- for left-align
- :---: for center-align
- ---: for right-align

```
| Project    | Stars | License    |
| :--------- | :---: | ---------: |
| **Alpha**  | 1024  | MIT        |
| **Beta**   |   76  | Apache-2.0 |
| **Gamma**  |    4  | GPL-3.0    |
```

Rendered:
| Project | Stars | License |
| :--------- | :---: | ---------: |
| **Alpha** | 1024 | MIT |
| **Beta** | 76 | Apache-2.0 |
| **Gamma** | 4 | GPL-3.0 |

### Strikethrough text

Need to mark something as obsolete? Instead of deleting it, GFM allows you to strikethrough portions of text. Simply wrap the text in double tildes `~~`:

```
~~This feature is now deprecated~~
```

Rendered:
~~This feature is now deprecated~~

### Mentions (@username)

GitHub lets you mention other users or teams to draw their attention. Typing `@` followed by a username or team name will create a mention.

```
Please review this change @octocat
```

Rendered:
Please review this change @octocat

In the rendered view, the mention becomes a clickable link to the user or team profile. Mentions are particularly useful in issues, pull requests, and comments, to ensure specific people see your message. _(Note: Users will only get notified if they have access to that particular repository or conversation.)_

## Coming Soon

Further content will be added to expand on advanced GFM features and best practices.
