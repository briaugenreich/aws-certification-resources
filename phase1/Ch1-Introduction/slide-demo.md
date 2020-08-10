layout: true
class: typo, typo-selection

---

count: false
class: center, middle

# remark it

A slideshow template powered by remarkjs

---

## Usage

1. Edit index.html and use markdown to write the slideshow.
.width-80[
  ![](static/1.png)
]

1. Double-click index.html to preview the slide effect.  
<small>Please refer to the [official documentation](https://github.com/gnab/remark/wiki) for presentation mode, timer, shortcut keys, etc</small>

---

## Typography

Technical presentation content mainly consists of text, code and a few pictures. Whether the font, size, color and spacing of text are comfortable or not, and whether there is good consistency plays a crucial role in the overall appearance and professionalism of the presentation. Using HTML to make presentations has a natural advantage in this area because all styles are controlled by CSS, making it easy to ensure consistency.

[typo.css](https://github.com/sofish/typo.css) provides a very professional and detailed typography style in both Chinese and English, which we can apply to global layout templates.

```markdown
layout: true
class: typo, typo-selection
```

---

exclude: true

## Typography Chinese sample

???
Use exclude: true to hide slides

---

## Typography sample

> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
> aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### The standard Lorem Ipsum passage, used since the 1500s

"Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
  aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

---


## Light Theme

<small>As a chapter page has a bit of literary style</small>

---

# Code sample

```ts
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css']
})
export class AppComponent {
*  isCollapsed = false; // highlighted by an asterisk at the beginning of line
   page = 9;
}
```

---


## Table sample

.st.noborder.st-hline.font-sm.mb-xs[
| Name | Price | Number |
| ---- | ---- | ----: |
| Banana | $1  | 5    |
| Apple | $1  | 6    |
| Strawberry | $1  | 7    |
]

.st.st-hline.font-sm.mb-xs[
| Name | Price | Number |
| ---- | ---- | ----: |
| Banana | $1  | 5    |
| Apple | $1  | 6    |
| Strawberry | $1  | 7    |
]

.column-2.column-norule[

.st.st-allline.font-sm.mb-xs[
| Name | Price | Number |
| ---- | ---- | ----: |
| Banana | $1  | 5    |
| Apple | $1  | 6    |
| .nord11[Strawberry] | .nord11[$1]  | .nord11[7]    |
]

.st.st-vline.font-sm.mb-xs[
| Name | Price | Number |
| ---- | ---- | ----: |
| Banana | $1  | 5    |
| Apple | $1  | 6    |
| Strawberry | $1  | 7    |
]

]

---

## Text alignment

.left[Left-aligned text]

.center[Centered text]

.right[Right-aligned text]

---
