# Headers
Headers indicate the start of a new section. There are 6 header sizes, each indicated by the number of hash symbols (#) used.

# This is an `<h1>` header
## This is an `<h2>` header
### This is an `<h3>` header
#### This is an `<h4>` header
##### This is an `<h5>` header
###### This is an `<h6>` header

# Images
You can also add images to markdown files by adding a hyperlink directly to the image. Short descriptions can also be added in between square brackets ([]) to either be read aloud for accessibility reasons or to be displayed when the connection is not strong enough to display the image.
![An image of a smiling cat](https://uploads.dailydot.com/2018/10/olli-the-polite-cat.jpg?auto=compress&fm=pjpg)

# Code Blocks
Code blocks format the content in a differently-colored space with a monospaced font to make it easy to distinguish as code. When a specific programming language is indicated, keywords can become color-coded to increase readability.

```
String myString = "Hello world!";
```

# Task List
Tasks lists are checklists you can add to markdown files or pull requests. They are especially helpful in keeping track of issues in the code. The syntax is slightly different for completed and uncompleted tasks.

- [x] Item 1
- [ ] Item 2
- [ ] Item 3


# Styling Text
You can also style text to emphasize certain parts or for better readability.

## Bold
| Syntax | Output |
| --- | --- |
| \*\*This is bold text\*\* | **This is bold text** |
| \_\_This is bold text\_\_ | __This is bold text__ |

You can also select the text and press `Command` + `B` (Mac) or `Ctrl` + `B` (Windows/Linux).

## Italic
| Syntax | Output |
| --- | --- |
| \*This is italicized text\* | *This is italicized text* |
| \_This is italicized text\_ | _This is italicized text_ |

You can also select the text and press `Command` + `I` (Mac) or `Ctrl` + `I` (Windows/Linux).

## Strikethrough
| Syntax | Output |
| --- | --- |
| \~\~This text was a mistake\~\~ | ~~This is italicized text~~ |

## Bold and Nested Italic
| Syntax | Output |
| --- | --- |
| \*\*This text is \_really\_ important\*\* | **This text is _really_ important** |

## All Bold and Italic
| Syntax | Output |
| --- | --- |
| \*\*\*But this text is much more important\*\*\* | ***But this text is much more important*** |

## Subscript
| Syntax | Output |
| --- | --- |
| This is \<sub>subscript\</sub> text | This is <sub>subscript</sub> text |

## Superscript
| Syntax | Output |
| --- | --- |
| This is \<sup>superscript\</sup> text | This is <sup>superscript</sup> text |

## Underline
| Syntax | Output |
| --- | --- |
| \<ins>This text is underlined\</ins> | <ins>This text is underlined</ins> |

# Quoting Text
You can use this formatting to point out information you are outsourcing. In the context of discussion posts, you can also use this when quote replying to someone else's message.

#### Syntax
\> This text is quoted
#### Output
> This text is quoted

# Quoting Code
There are two ways of quoting code:
 1. Inline = quoting text within a line of text
 2. Code block = quoting multiple lines of code

### Inline 
Inline quoting of text is especially useful in cases where you want to highlight functions/commands or mention keyboard shortcuts.

#### Syntax
\`git status\`
#### Output
`git status`

### Code Block 
Quoting multiple lines of code will separate the content in its own section with a different style. 

#### Syntax
\`\`\`<br>
git status<br>
git add<br>
git commit<br>
\`\`\`

#### Output
```
git status
git add
git commit
```

### Syntax Highlighting
You can specify a programming language to enable color coding of the source code. 

#### Syntax
\`\`\`HTML<br>
\<h1>This is a header\</h1><br>
\<p>This is a paragraph\</p><br>
\`\`\`

#### Output
```HTML
<h1>This is a header</h1>
<p>This is a paragraph</p>
```

# Supported Color Models
**Note: This feature is only supported in issues, pull requests, and discussions. The examples below will not be able to show the output expected in these scenarios.<br>
This feature enables you to show a color code and its swatch. The currently supported color models are HEX, RGB, and HSL.

| Syntax | Output |
| --- | --- |
| \`#FFB3F5\` | `#FFB3F5` |
| \`rgb(109,5,252)\`| `rgb(109,5,252)` |
| \`hsl(173,100%,50%)\`| `hsl(173,100%,50%)` |



















