# Markdown Quick Recap Sheet

This repository is a quick reference for Markdown syntax and features you can use to create professional README files.

Feel free to **star** ⭐ this repository if you find it useful.

[My GitHub Profile](https://github.com/rishabhkumaar)
[Markdown Repository](https://github.com/rishabhkumaar/markdown)

---

## Headings

# H1 Heading

## H2 Heading

### H3 Heading

#### H4 Heading

##### H5 Heading

###### H6 Heading

---

## Text Formatting

**Bold Text**
*Italic Text*
***Bold and Italic Text***
~~Strikethrough Text~~

> This is a blockquote
>
> > Nested blockquote for deeper thoughts

Inline code: `Use backticks for code-like text`

---

## Lists

### Unordered List

* Item A

  * Subitem A.1

    * Sub-subitem A.1.a
* Item B

- Item C

* Item D

### Ordered List

1. First item
2. Second item

   1. Sub-item 2.1
   2. Sub-item 2.2
3. Third item

---

## Links

[GitHub](https://github.com/rishabhkumaar)
Auto-linked: [https://www.github.com](https://www.github.com)

Reference-style:
[Google][1]

[1]: https://www.google.com

---

## Images

Basic Image:
![Placeholder](resource/demo1.png)

Image with Title Tooltip:
![GitHub Demo](resource/demo2.png "Demo Image")

Image as a Link:
[![](resource/demo3.png)](https://github.com/rishabhkumaar)

---

## Code and Code Blocks

### Inline Code

Use backticks `` ` `` for inline `code`.

### Multi-language Code Blocks

#### JavaScript

```js
// Greet function
function greet(name) {
  return `Hello, ${name}!`;
}
console.log(greet("World"));
```

#### Python

```python
# Greet function
def greet(name):
    return f"Hello, {name}!"

print(greet("World"))
```

---

## Tables

| Name    | Role      | Location |
| ------- | --------- | -------- |
| Rishabh | Student   | India    |
| Alex    | Developer | USA      |
| Marie   | Designer  | France   |

**Alignment Example**

| Left Align | Center Align | Right Align |
| :--------- | :----------: | ----------: |
| Item A     |    Item B    |      Item C |
| Text       |   More Text  |     Aligned |

---

## Task Lists

* [x] Completed Task
* [ ] Pending Task
* [ ] Another Task

  * [x] Subtask Done
  * [ ] Subtask Pending

---

## Footnotes

This is an example sentence with a footnote.[^1]

Another one here.[^note]

[^1]: This is the first footnote.

[^note]: You can add multiple footnotes like this.

---

## Advanced Markdown Features

### Collapsible Sections

<details>
  <summary>Click to Expand</summary>

Hidden content goes here.
You can include text, images, or even code blocks inside collapsible sections.

```python
print("Hello from inside a collapsible section!")
```

</details>

---

### Table of Contents (Manual Example)

* [Headings](#headings)
* [Text Formatting](#text-formatting)
* [Lists](#lists)
* [Links](#links)
* [Images](#images)
* [Code and Code Blocks](#code-and-code-blocks)
* [Tables](#tables)
* [Task Lists](#task-lists)
* [Footnotes](#footnotes)
* [Advanced Markdown Features](#advanced-markdown-features)
* [Best Practices for README](#best-practices-for-readmemd)
* [About the Author](#about-the-author)
* [Contributing](#contributing)

---

### Math Formulas (LaTeX Style)

Inline: \$E = mc^2\$

Block:

```math
\int_{a}^{b} f(x) dx = F(b) - F(a)
```

---

### Horizontal Dividers

```
---
***
___
```

They render as:

---

---

---

---

### Badges

Example using Shields.io:

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-MIT-orange)

---

## Best Practices for README.md

A great README is the **front door of your project**. Follow these tips:

1. **Start with a Clear Title & Description**

   * A one-line explanation of what your project does.
   * Add badges (build, version, license) at the top.

2. **Add a Table of Contents**

   * Useful for long projects. Helps users navigate quickly.

3. **Installation & Usage Instructions**

   * Show step-by-step installation commands.
   * Provide code examples for usage.

4. **Screenshots / Demos**

   * A picture or GIF often explains better than words.

5. **Project Structure**

   ```bash
   project-name/
   ├── src/
   ├── docs/
   ├── tests/
   ├── README.md
   └── LICENSE
   ```

6. **Contributing Guidelines**

   * Add a `CONTRIBUTING.md` file.
   * Explain how others can contribute.

7. **License Information**

   * Always specify your license (MIT, Apache 2.0, etc.).

8. **Contact / Author Info**

   * Links to GitHub, LinkedIn, or website.

---

## About the Author

**Rishabh Kumar**
Student, Developer, and Open-Source Enthusiast.
Passionate about learning, sharing knowledge, and building useful projects.

* [GitHub](https://github.com/rishabhkumaar)
* [LinkedIn](https://www.linkedin.com/in/rishabhkumaar)

---

## Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a pull request to improve this cheat sheet.

---

## A Quick to Use [TEMPLATE](TEMPLATE.md) for README.md