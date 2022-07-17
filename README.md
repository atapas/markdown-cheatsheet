
# Table of Contents
` markdown-cheatsheet` is a single place for all the markdown syntaxes I have learned so far. Sharing publicly so that you also know about them and use.

1. [Headings](#headings)
2. [Code](#code)
3. [Unordered List of Items](#unordered-list-of-items)
4. [Ordered List of Items](#ordered-list-of-items)
5. [CheckBox Task List](#checkbox-task-list)
6. [Code Block](#code-block)
7. [Strikethrough Text](#strikethrough-text)
8. [Blockquote Text](#blockquote-text)
9. [Bold](#bold)
10. [Italic](#italic)
11. [Bold and Italic](#bold-and-italic)
12. [Link](#link)
13. [Image](#image)
14. [Linking an Image](#linking-an-image)
15. [Emojis](#emojis)
16. [Table](#table)
17. [Table With Alignments](#table-with-alignments)
18. [Horizontal Line](#horizontal-line)
19. [HTML](#html)
20. [Embed YouTube Video](#embed-youtube-video)
21. [Mathematical Expressions](#mathematical-expressions)

Many Thanks to all the `Stargazers` who has supported this project with stars(⭐)

[![Stargazers repo roster for @atapas/markdown-cheatsheet](https://reporoster.com/stars/atapas/markdown-cheatsheet)](https://github.com/atapas/markdown-cheatsheet/stargazers)

## Headings

**Syntax:**

```
# H1 - Heading 1
## H2 - Heading 2
### H3 - Heading 3
#### H4 - Heading 4
##### H5 - Heading 5
###### H6 - Heading 6
```
**Output:**

# H1 - Heading 1
## H2 - Heading 2
### H3 - Heading 3
#### H4 - Heading 4
##### H5 - Heading 5
###### H6 - Heading 6

## Code

**Syntax:**

```
`This is Code`
```

**Output:**

`This is Code`

## Unordered List of Items

**Syntax:**

```
- Milk
- Tea
- Beer
```

**Output:**

- Milk
- Tea
- Beer

**Syntax:**
> This is an alternate syntax to create unordered list items.

```
* JavaScript
* TypeScript
* ReactJs
```

**Output:**

* JavaScript
* TypeScript
* ReactJs

## Ordered List of Items

**Syntax:**

```
1. Eat
1. Walk
1. Sleep
```

**Output:**

1. Eat
1. Walk
1. Sleep

## CheckBox Task List

**Syntax:**

```
- [X] Code
- [ ] Review
- [ ] Commit
```

**Output:**

- [X] Code
- [ ] Review
- [ ] Commit

## Code Block

**Syntax:**

````
```
This is a code block. You can create for code syntaxes like JavaScript, HTML, CSS, Bash, and many more.
```
````

**Output:**
```
This is a code block. You can create for code syntaxes like JavaScript, HTML, CSS, Bash, and many more.
```

In order to ***highlight the code***, you can add language name at the start of the backticks as in the following examples.

**Example 1:**

````
```js
function print() {
 console.log('This is is a JavaScript Code Block');
}
```
````

**Output:**
```js
function print() {
 console.log('This is is a JavaScript Code Block');
}
```

**Example 2:**

````
```bash
# This is bash
echo 1
```
````

**Output:**
```bash
# This is bash
echo 1
```

## Strikethrough Text

**Syntax:**

```
~~Sharing is NOT about Caring.~~
```

**Output:**

~~Sharing is NOT about Caring.~~

## Blockquote Text

**Syntax:**

```
> When I say something, I mean it. When I mean it, I do it. When I do, I may fail. When I fail, I start talking about it again!
```

**Output:**

> When I say something, I mean it. When I mean it, I do it. When I do, I may fail. When I fail, I start talking about it again!

## Bold

**Syntax:**

```
**DO NOT UNDERESTIMATE THE POWER OF A PROGRAMMER.**
```

**Output:**

**DO NOT UNDERESTIMATE THE POWER OF A PROGRAMMER.**

## Italic

**Syntax:**

```
*It is Written in Italics*
```

**Output:**

*It is Written in Italics*

## Bold and Italic

**Syntax:**

```
***You Can Combine Bold and Italics***
```

**Output:**

***You Can Combine Bold and Italics***

## Link

**Syntax:**

```
Did you know I have [Website](https://tapasadhikary.com)?
```

**Output:**

Did you know I have [Website](https://tapasadhikary.com)?

## Image

**Syntax:**

```
![alt text](image)
```

**Output:**

![GreenRoots Blog](https://res.cloudinary.com/atapas/image/upload/v1598936159/profile/500x500_oklccx.png)

## Linking an Image

**Syntax:**

```
[![alt text](image)](hyperlink)
```

**Output:**

[![GreenRoots Blog](https://res.cloudinary.com/atapas/image/upload/v1598936159/profile/500x500_oklccx.png)](https://blog.greenroots.info)

## Emojis

**Syntax:**

```
:mango: :lemon: :man: :car:
```

**Output:**

:mango: :lemon: :man: :car:

## Table

**Syntax:**

```
| Fruit | Emoji |
| ----------- | ----------- |
| Mango | :mango: |
| Lemon | :lemon: |
```

**Output:**


| Fruit | Emoji |
| ----------- | ----------- |
| Mango | :mango: |
| Lemon | :lemon: |

## Table With Alignments

**Syntax:**

```
| Fruit(left)      | Emoji(center) | Taste(right)     |
| :---        |    :----:   |          ---: |
| Mango is the king of Fruits      | :mango:       | Sweet and I love it  |
| Lemon is good for health   | :lemon:        | Sour, mix it in the water     |
```

**Output:**

| Fruit(left)      | Emoji(center) | Taste(right)     |
| :---        |    :----:   |          ---: |
| Mango is the king of Fruits      | :mango:       | Sweet and I love it  |
| Lemon is good for health   | :lemon:        | Sour, mix it in the water     |

## Horizontal Line

**Syntax:**

```
---
```

**Output:**

---

## HTML

**Syntax:**

```
<p align="center">
 Yes, you can use allowed raw HTML in mark-down file.
 This is a paragraph aligned in the center.
</p>
```

**Output:**

<p align="center">
 Yes, you can use allowed raw HTML in mark-down file.
 This is a paragraph aligned in the center.
</p>

<details>
    <summary>Heading</summary>
    The details are here.
</details>

## Embed YouTube Video

**Syntax:**

```
[![Alt Text](Thumbnail Image)](YOUTUBE VIDEO LINK)
```

**Output:**

[![Forking a Repo](https://res.cloudinary.com/atapas/image/upload/v1654144800/demos/Merge-Conflicts_vtk8on.png)](https://www.youtube.com/watch?v=OulZeVtZhZQ)

## Mathematical Expressions

1. **Inline expressions:**

    **Syntax**

    ```plain
    $<<mathematical expression>>$
    ```

    Replace `<<mathematical expression>>` with your expression.

    **Example**

    ```plain
    $\sqrt{3}+1$
    ```

    **Output**

    $\sqrt{3}+1$

2. **Block Expressions:**

    **Syntax**

    ```plain
    $$<<mathematical expression>>$$
    ```

    **Example**

    ```plain
    $$\sqrt{3}+1$$
    ```

    **Output**

    $$\sqrt{3}+1$$

3. **Mixed Expressions:**

    **Syntax**
    
    ```
    When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are 
    
    $$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$
    ```

    **Output**

    When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are 
    
    $$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

For more information on how to write mathematical expressions, [visit this page](https://en.wikibooks.org/wiki/LaTeX/Mathematics).


