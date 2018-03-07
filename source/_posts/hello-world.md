---
title: hello-world
abbrlink: b1d4025b
date: 2018-03-07 12:54:50
tags:
---

![picture](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Haskell-Logo.svg/640px-Haskell-Logo.svg.png?1520401748934 "Optional title")


# h1

## h2

### h3

#### h4

##### h5

###### h6

> 引用

* 1
    * 1.1
    * 2.2
* 2
* 3

1. 1
    1) 1.1
    2) 2.2
2. 2
3. 3


```javascript
function test() {
  console.log("notice the blank line before this function?");
}
```

inline math: $\lim_{x \to \infty} \exp (-x) = 0$.

$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

You can create footnotes like this[^footnote].

[^footnote]: Here is the *text* of the **footnote**.

This is [an example](http://example.com/ "Title") inline link.

***

[This link](http://example.net/) has no title attribute.

This is [an example][id] reference-style link.

Then, anywhere in the document, you define your link label like this, on a line by itself:

[id]: http://example.com/  "Optional Title Here"

[Google][]
And then define the link:

[Google]: http://google.com/

---

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

inline code `hello world`

~~Mistaken text.~~

<u>Underline</u>

H~2~O

X^2^
