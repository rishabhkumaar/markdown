# 📚 Markdown Quick Recap Sheet

## 🏷️ Headings

# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading

---

## ✍️ Text Formatting

**Bold Text**  
*Italic Text*  
***Bold and Italic Text***  
~~Strikethrough Text~~  

> This is a blockquote  
>> Nested blockquote for deeper thoughts

Inline quote: `Use backticks for code-like text`

---

## 📋 Lists

### 🔸 Unordered List
- Item A
  - Subitem A.1
    - Sub-subitem A.1.a
- Item B
* Item C
+ Item D

### 🔢 Ordered List
1. First item
2. Second item
   1. Sub-item 2.1
   2. Sub-item 2.2
3. Third item

---

## 🔗 Links

[GitHub](https://github.com/rishabhkumaar)  
[GitHub (Auto-linked)](https://www.github.com)

Reference-style:  
[Google][1]

[1]: https://www.google.com

---

## 🖼️ Images

Basic Image:  
![Placeholder](resource/demo1.png)

Image with Title Tooltip:  
![GitHub Demo](resource/demo2.png "Demo Image")

Image as a link:  
[![](resource/demo3.png)](https://github.com/rishabhkumaar)

---

## `Code` & Code Blocks

### Inline `code`

Use backticks `` ` `` for inline `code`.

### Multi-language Code Blocks

#### JavaScript
```js
// Greet function
function greet(name) {
  return `Hello, ${name}! 👋`;
}
console.log(greet("World"));
```

#### Python
```python
# Greet function
def greet(name):
    return f"Hello, {name}! 👋"

print(greet("World"))
```