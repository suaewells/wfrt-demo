# Example Markdown

## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___

---

***


## Typographic replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
- Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
return bar++;
};

console.log(foo(5));
```

$$
\frac{\partial u}{\partial t}=-u \frac{\partial u}{\partial x}-v \frac{\partial u}{\partial y}-w \frac{\partial u}{\partial z}+\frac{u v \tan \phi}{a}-\frac{u w}{a}-\frac{1}{\rho} \frac{\partial p}{\partial x}-2 \Omega(w \cos \phi-v \sin \phi)+F r_{x}  
$$

<br>

$$
\frac{\partial v}{\partial t}=-u \frac{\partial v}{\partial x}-v \frac{\partial v}{\partial y}-w \frac{\partial v}{\partial z}-\frac{u^{2} \tan \phi}{a}-\frac{u w}{a}-\frac{1}{\rho} \frac{\partial p}{\partial y}-2 \Omega u \sin \phi+F r_{y} 
$$

<br>

$$
\frac{\partial w}{\partial t}=-u \frac{\partial w}{\partial x}-v \frac{\partial w}{\partial y}-w \frac{\partial w}{\partial z}-\frac{u^{2}+v^{2}}{a}-\frac{1}{\rho} \frac{\partial p}{\partial z}+2 \Omega u \cos \phi-g+F r_{z} 
$$

<br>

$$
\frac{\partial T}{\partial t}=-u \frac{\partial T}{\partial x}-v \frac{\partial T}{\partial y}+\left(\gamma-\gamma_{d}\right) w+\frac{1}{c_{p}} \frac{d H}{d t}  
$$

<br>

$$
\frac{\partial \rho}{\partial t}=-u \frac{\partial \rho}{\partial x}-v \frac{\partial \rho}{\partial y}-w \frac{\partial \rho}{\partial z}-\rho\left(\frac{\partial u}{\partial x}+\frac{\partial v}{\partial y}+\frac{\partial w}{\partial z}\right)
$$

<br>

$$
\frac{\partial q_{v}}{\partial t}=-u \frac{\partial q_{v}}{\partial x}-v \frac{\partial q_{v}}{\partial y}-w \frac{\partial q_{v}}{\partial z}+Q_{v}  
$$

<br>

$$
P=\rho R T  
$$