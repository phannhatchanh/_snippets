---
date: 2022-01-02
name: 'List Styles'
description: 'Làm cho các dấu đầu dòng của thẻ ul hay ol đẹp hơn với CSS'
category: 'HTML & CSS'
slug: 'reference-list-styles-ul-ol-li-with-css'
---

Nếu bạn thường xuyên sử dụng thẻ `<ul>` hay `<ol>` để tạo ra danh sách liệt kê trên trang web của mình. Bạn có thể dễ dàng định dạng nó nếu như bạn biết css. Nếu không, bạn cũng có thể lựa chọn và sử dụng các mẫu được định dạng bằng css mà tôi đã liệt kê sẵn dưới đây cho trang web của bạn.

## HTML
Đầu tiên ta sẽ có mã cho trang HTML để liệt kê ra một danh sách như: HTML, CSS, Photoshop, Illustrator như dưới đây (nếu bạn đánh số một list thì bạn sử dụng `<ol>`) và nó sẽ áp dụng chung cho các css bên dưới.
```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>Photoshop</li>
  <li>Illustrator</li>
</ul>
```

> Các đoạn CSS dưới đây có sử dụng Font Awesome 5. Nếu bạn sử dụng phiên bản củ hơn thì bạn chỉ việc thay đổi **font-family: "Font Awesome 5 Free";** thành **font-family: "FontAwesome";**

## CSS

<details><summary>Code CSS - Mẫu 1</summary>

```css
ul, ol {
  background: #fcfcfc;
  padding: 0.5em 0.5em 0.5em 2em;
  border: solid 3px gray;
}

ul li, ol li {
  line-height: 1.5;
  padding: 0.5em 0;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-1.png 'List style - Template 1')

---
<details><summary>Code CSS - Mẫu 2</summary>

```css
ul, ol {
  color: #668ad8;
  border: dashed 2px #668ad8;
  background: #f1f8ff; 
  padding: 0.5em 0.5em 0.5em 2em;
}

ul li, ol li {
  line-height: 1.5;
  padding: 0.5em 0;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-2-1.png 'List style - Template 2')
---
<details><summary>Code CSS - Mẫu 3</summary>

```css
ul, ol {
  color: #668ad8; 
  border: double 5px #668ad8;
  background: #f1f8ff; 
  padding: 0.5em 0.5em 0.5em 2em;
}

ul li, ol li {
  line-height: 1.5;
  padding: 0.5em 0;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-2-2.png 'List style - Template 3')

---
<details><summary>Code CSS - Mẫu 4</summary>

```css
ul, ol {
  color: #1e366a;
  border-top: solid #1e366a 1px;
  border-bottom: solid #1e366a 1px;
  padding: 0.5em 0 0.5em 1.5em;
}

ul li, ol li {
  line-height: 1.5;
  padding: 0.5em 0;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-3.png 'List style - Template 4')

---
<details><summary>Code CSS - Mẫu 5</summary>

```css
ul, ol {
  color: #1e366a;
  border: dotted #1e366a 1px;
  padding: 0.5em 0.5em 0.5em 2em;
}

ul li, ol li {
  line-height: 1.5;
  padding: 0.5em 0;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-4.png 'List style - Template 5')

---
<details><summary>Code CSS - Mẫu 6</summary>

```css
ul, ol {
  background: #fffcf4;
  border-radius :8px;
  box-shadow :0px 0px 5px silver;
  padding: 0.5em 0.5em 0.5em 2em;
}
ul li, ol li {
  line-height: 1.5;
  padding: 0.5em 0;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-5-1.png 'List style - Template 6')

---
<details><summary>Code CSS - Mẫu 7</summary>

```css
ul, ol {
  background: #dadada;
  border-radius :8px;
  box-shadow :0px 0px 5px silver;
  padding: 0.5em 0.5em 0.5em 2em;
}
ul li, ol li {
  line-height: 1.5;
  padding: 0.5em 0;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-5-2.png 'List style - Template 7')

---
<details><summary>Code CSS - Mẫu 8</summary>

```css
ul, ol {
  background: #fffde8;
  box-shadow: 0px 0px 0px 10px #fffde8;
  border: dashed 2px #ffb03f;
  border-radius: 9px;
  margin-left: 10px;
  margin-right: 10px;
  padding: 0.5em 0.5em 0.5em 2em;
}

ul li, ol li {
  line-height: 1.5;
  padding: 0.5em 0;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-6-1.png 'List style - Template 8')

---
<details><summary>Code CSS - Mẫu 9</summary>

```css
ul, ol {
  background: #f1f8ff;
  box-shadow: 0px 0px 0px 10px #f1f8ff;
  border: dashed 2px #668ad8;
  border-radius: 9px;
  margin-left: 10px;
  margin-right: 10px;
  padding: 0.5em 0.5em 0.5em 2em;
}

ul li, ol li {
  line-height: 1.5;
  padding: 0.5em 0;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-6-2.png 'List style - Template 9')

---
<details><summary>Code CSS - Mẫu 10</summary>

```css
ul, ol {
  padding: 0;
  position: relative;
}

ul li, ol li {
  color: #2d8fdd;
  border-left: solid 6px #2d8fdd;
  background: #f1f8ff;
  margin-bottom: 3px;
   line-height: 1.5;
  padding: 0.5em;
  list-style-type: none!important;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-7-1.png 'List style - Template 10')

---
<details><summary>Code CSS - Mẫu 11</summary>

```css
ul, ol {
  padding: 0;
  position: relative;
}

ul li, ol li {
  color: black;
  border-left: solid 8px orange;
  background: whitesmoke;
  margin-bottom: 5px;
  line-height: 1.5;
  border-radius: 0 15px 15px 0;
  padding: 0.5em;
  list-style-type: none!important;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-7-2.png 'List style - Template 11')

---
<details><summary>Code CSS - Mẫu 12</summary>

```css
ul {
  padding: 0;
}

ul li, ol li {
  color: #404040;
  border-left: solid 6px #1fa67a;
  border-bottom: solid 2px #dadada;
  background: whitesmoke;
  margin-bottom: 5px;
  line-height: 1.5;
  padding: 0.5em;
  list-style-type: none!important;
  font-weight: bold;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-7-3.png 'List style - Template 12')

---
<details><summary>Code CSS - Mẫu 13</summary>

```css
ul, ol {
  padding: 0;
}

ul li {
  position: relative;
  list-style-type: none!important;
  padding: 0.5em 0.5em 0.5em 0.5em;
  margin-bottom: 5px;
  line-height: 1.5;
  background: #dbebf8;
  vertical-align: middle;
  color: #505050;
  border-radius: 15px 0px 0px 15px;
}

ul li:before{ 
  display:inline-block; 
  vertical-align: middle;

  content:'';
  width:1em;
  height: 1em;
  background: #fff;
  border-radius: 50%;
  margin-right: 8px;
}
```
</details>

![style ul ol li với css](./list-ul-ol-style-8.png 'List style - Template 13')

---
<details><summary>Code CSS - Mẫu 14</summary>

```css
ul {
  border: solid 2px skyblue;
  border-radius: 5px;
  padding: 0.5em 1em 0.5em 2.3em;
  position: relative;
}

ul li {
  line-height: 1.5;
  padding: 0.5em 0;
  list-style-type: none!important;
}

ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f138";/
  position: absolute;
  left : 1em;
  color: skyblue;
}
```
</details>

![style ul ol li với css](./2-1-list-ul-ol-style.png 'List style - Template 14')

---
<details><summary>Code CSS - Mẫu 15</summary>

```css
ul {
  border: solid 2px skyblue;
  padding: 0.5em 1em 0.5em 2.3em;
  position: relative;
}

ul li {
  line-height: 1.5;
  padding: 0.5em 0;
  list-style-type: none!important;
}

ul li:before {
  
  font-family: "Font Awesome 5 Free";
  content: "\f075";
  position: absolute;
  left : 1em;
  color: skyblue; 
}
```
</details>

![style ul ol li với css](./2-2-list-ul-ol-style.png 'List style - Template 15')

---
<details><summary>Code CSS - Mẫu 16</summary>

```css
ul {
  border: solid 2px #ffb03f;
  padding: 0.5em 1em 0.5em 2.3em;
  position: relative;
}

ul li {
  line-height: 1.5;
  padding: 0.5em 0;
  list-style-type: none!important;
}

ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f00c";
  position: absolute;
  left : 1em; 
  color: #ffb03f; 
}
```
</details>

![style ul ol li với css](./2-3-list-ul-ol-style.png 'List style - Template 16')

---
<details><summary>Code CSS - Mẫu 17</summary>

```css
ul {
  border: double 4px #21b384;
  padding: 0.5em 1em 0.5em 2.3em;
  position: relative;
}
ul li {
  line-height: 1.5;
  padding: 0.5em 0;
  list-style-type: none!important;
}
ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f0a4";
  position: absolute;
  left : 1em; 
  color: #21b384; 
}
```
</details>

![style ul ol li với css](./2-4-list-ul-ol-style.png 'List style - Template 17')

---
<details><summary>Code CSS - Mẫu 18</summary>

```css
ul {
  border: solid 2px #ff938b;
  background: #fffaf1;
  padding: 0.5em 1em 0.5em 2.3em;
  position: relative;
}

ul li {
  line-height: 1.5;
  padding: 0.5em 0;
  list-style-type: none!important;
}

ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f1b0";
  position: absolute;
  left : 1em; 
  color: #ff938b; 
}
```
</details>

![style ul ol li với css](./2-5-list-ul-ol-style.png 'List style - Template 18')

---
<details><summary>Code CSS - Mẫu 19</summary>

```css
ul {
  box-shadow :0px 0px 3px silver;
  border: solid 1px whitesmoke;
  padding: 0.5em 1em 0.5em 2.3em;
  position: relative;
  background: #fafafa;
}

ul li {
  line-height: 1.5;
  padding: 0.5em 0;
  list-style-type: none!important;
}

ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f0da";
  position: absolute;
  left : 1em; 
  color: gray; 
}
```
</details>

![style ul ol li với css](./2-6-list-ul-ol-style.png 'List style - Template 19')

---
<details><summary>Code CSS - Mẫu 20</summary>

```css
ul {
  padding: 0;
  position: relative;
}

ul li {
  line-height: 1.5;
  padding: 0.5em 0.5em 0.5em 1.7em;
  list-style-type: none!important;
  background: -webkit-linear-gradient(top, #whitesmoke 0%, whitesmoke 100%);
  background: linear-gradient(to bottom, whitesmoke 0%, #dadada 100%);
  text-shadow: 1px 1px 1px whitesmoke;
  color: black;
}

ul li:before { 
  font-family: "Font Awesome 5 Free";
  content: "\f138";
  position: absolute;
  left : 0.5em; 
  color: orange; 
}
```
</details>

![style ul ol li với css](./2-7-a-list-ul-ol-style.png 'List style - Template 20')

---
<details><summary>Code CSS - Mẫu 21</summary>

```css
ul {
  padding: 0;
  position: relative;
}
ul li {
  line-height: 1.5;
  padding: 0.5em 0.5em 0.5em 1.7em;
  list-style-type: none!important;
  background: -webkit-linear-gradient(top, skyblue 0%, #5aade6 100%);
  background: linear-gradient(to bottom, skyblue 0%, #5aade6 100%);
  color: #fff;
}

ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f138";
  position: absolute;
  left : 0.5em;
  color: white;
}
```
</details>

![style ul ol li với css](./2-7-b-list-ul-ol-style.png 'List style - Template 21')

---
<details><summary>Code CSS - Mẫu 22</summary>

```css
ul {
  border: solid 2px #ffb03f;
  padding: 0 0.5em;
  position: relative;
}

ul li {
  line-height: 1.5;
  padding: 0.5em 0 0.5em 1.4em;
  border-bottom: dashed 1px silver;
  list-style-type: none!important;
}

ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f138";
  position: absolute;
  left : 0.5em; 
  color: #ffb03f; 
}

ul li:last-of-type {
  border-bottom: none;
}
```
</details>

![style ul ol li với css](./2-8-a-list-ul-ol-style.png 'List style - Template 22')

---
<details><summary>Code CSS - Mẫu 23</summary>

```css
ul {
  background: whitesmoke;
  padding: 0 0.5em;
  position: relative;
}

ul li {
  line-height: 1.5;
  padding: 0.5em 0 0.5em 1.5em;
  border-bottom: 2px solid white;
  list-style-type: none!important;
}

ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f00c";
  position: absolute;
  left : 0.5em; 
  color: #668ad8; 
}

ul li:last-of-type {
  border-bottom: none;
}
```
</details>

![style ul ol li với css](./2-8-b-list-ul-ol-style.png 'List style - Template 23')

---
<details><summary>Code CSS - Mẫu 24</summary>

```css
ul {
  padding: 0;
  position: relative;
}

ul li {
  color: white;
  background: #81d0cb;
  line-height: 1.5;
  padding: 0.5em 0.5em 0.5em 2em;
  border-bottom: 2px solid white;
  list-style-type: none!important;
  font-weight: bold; 
}

ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f14a";
  position: absolute;
  left : 0.5em; 
  color: white; 
}
```
</details>

![style ul ol li với css](./2-9-a-list-ul-ol-style.png 'List style - Template 24')

---
<details><summary>Code CSS - Mẫu 25</summary>

```css
ul {
  padding: 0;
  position: relative;
}
ul li {
  color: white;
  background   
}
ul li:last-of-type {
  border-bottom: none;
}
```
</details>

![style ul ol li với css](./2-9-b-list-ul-ol-style.png 'List style - Template 25')

---
<details><summary>Code CSS - Mẫu 26</summary>

```css
ul {
  padding: 0;
}

ul li {
  color: black;
  position:relative;
  background: #f1f8ff;
  line-height: 1.5;
  padding: 0.5em;
  margin-bottom: 4px 
  
}

ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f303";
  position: absolute;
  display: block;
  padding: 0.5em;
  width: 1.2em;
  color: white; 
  font-weight: normal;
  text-align: center;
  left 
  
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
}
```
</details>

![style ul ol li với css](./2-9-c-list-ul-ol-style.png 'List style - Template 26')

---
<details><summary>Code CSS - Mẫu 27</summary>

```css
ol {
  counter-reset:number; 
  list-style-type: none!important; 
  padding:0.5em;
  background
}
ol li {
  position: relative;
  padding-left: 30px;
  line-height: 1.5em;
  padding: 0.5em 0.5em 0.5em 
}

ol li:before{
  position: absolute;
  counter-increment: number;
  content: counter(number);

  display:inline-block;
  background: #5c9ee7;
  color: white;
  font-family: 'Avenir','Arial Black','Arial',sans-serif;
  font-weight:bold;
  font-size: 15px;
  border-radius: 50%;
  left: : 25px;
  height: 25px;
  line-height: 25px;
  text-align: center;

  top: 50%;
  -webkit-transform: translateY(-50%);
  transform
}
```
</details>

![style ul ol li với css](./3-1-a-list-ul-ol-style.png 'List style - Template 27')

---
<details><summary>Code CSS - Mẫu 28</summary>

```css
ol {
  counter-reset:number; 
  list-style-type: none!important; 
  padding: 0.3em 0.8em;
  border: solid 2px 
}
ol li {
  border-bottom: dashed 1px orange;
  position: relative;
  padding: 0.5em 0.5em 0.5em 30px;
  line-height: 
}
ol li:before{
  position: absolute;
  counter-increment: number;
  content: counter(number);

  display:inline-block;
  background: #ffb107;
  color: white;
  font-family: 'Avenir','Arial Black','Arial',sans-serif;
  font-weight:bold;
  font-size: 15px;
  border-radius: 50%;
  left: 0;
  width: 25px;
  height: 25px;
  line-height: 25px;
  text-align: center;

  top: 50%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
}
ol li:last-of-type {
  border-bottom: none; 
}
```
</details>

![style ul ol li với css](./3-1-b-list-ul-ol-style.png 'List style - Template 28')

---
<details><summary>Code CSS - Mẫu 29</summary>

```css
ol {
  counter-reset:number; 
  list-style-type: none!important; 
  padding:0.5em;
  border: dashed 1px gray;
}

ol li {
  position: relative;
  line-height: 1.5em;
  padding: 0.5em 0.5em 0.5em 30px;
}

ol li:before{
  position: absolute;
  counter-increment: number;
  content: counter(number);

  display:inline-block;
  background: #74c2f8;
  color: white;
  font-family: 'Avenir','Arial Black','Arial',sans-serif;
  font-weight:bold;
  font-size: 15px;
  left: 0;
  width: 25px;
  height: 25px;
  line-height: 25px;
  text-align: center;

  top: 50%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
}
```
</details>

![style ul ol li với css](./3-2-a-list-ul-ol-style.png 'List style - Template 29')

---
<details><summary>Code CSS - Mẫu 30</summary>

```css
ol {
  counter-reset:number;
  list-style-type: none!important;
  padding:0;
}
ol li {
  position: relative;
  padding: 0.5em;
  line-height: 1.5em;
  background: #f1f8ff;
  border-left : solid 35px #5c9ee7;
  margin-bottom: 5px;
}
ol li:before{
  position: absolute;
  counter-increment: number;
  content: counter(number);

  display:inline-block;
  color: white;
  font-family: 'Avenir','Arial Black','Arial',sans-serif;
  font-weight:bold;
  font-size: 15px;
  top: 50%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
  left: -35px;
  width: 35px;
  height: 1em;
  line-height: 1;
  text-align: center;
}
```
</details>

![style ul ol li với css](./3-2-b-list-ul-ol-style.png 'List style - Template 30')

---
<details><summary>Code CSS - Mẫu 31</summary>

```css
ol {
  counter-reset:number; 
  list-style-type: none!important; 
  padding:0;
  border-top: solid 2px black;
  border-bottom: solid 2px black;
}
ol li {
  padding: 0.5em 0;
  position: relative;
  padding-left: 1.4em;
  line-height: 1.5em;
}
ol li:before{
  counter-increment: number;
  content: counter(number) ".";
  position: absolute;
  left: 0;
  font-family: 'Bradley Hand','Segoe Script','Segoe Print',sans-serif;
  font-size: 1.3em;
}
```
</details>

![style ul ol li với css](./3-3-list-ul-ol-style.png 'List style - Template 31')

---
<details><summary>Code CSS - Mẫu 32</summary>

```css
ol {
  counter-reset:number; 
  list-style-type: none!important; 
  padding:0.5em;
  border: solid 2px #5c9ee7;
}
ol li {
  position: relative;
  padding: 0.5em 0.5em 0.5em 35px;
  line-height: 1.5em;
}
ol li:before{
  position: absolute;
  counter-increment: number;
  content: counter(number);

  display:inline-block;
  background: #5c9ee7;
  color: white;
  font-family: 'Avenir','Arial Black','Arial',sans-serif;
  font-weight:bold;
  font-size: 15px;
  border-radius: 50%;
  left: 0;
  width: 25px;
  height: 25px;
  line-height: 25px;
  text-align: center;

  top: 50%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
}
ol li:after {
  content: '';
  display: block;
  position: absolute;
  left: 20px;
  height: 0;
  width: 0;
  border-top: 7px solid transparent;
  border-bottom: 7px solid transparent;
  border-left: 12px solid #5c9ee7;

  top: 50%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
}
```
</details>

![style ul ol li với css](./3-4-list-ul-ol-style.png 'List style - Template 32')

---
<details><summary>Code CSS - Mẫu 33</summary>

```css
ul {
  border: solid 2px #ffb03f;
  padding: 0.5em;
  position: relative;
  margin-top: 2em;
}
ul li {
  line-height: 1.5;
  padding: 0.5em 0 0.5em 1.4em;
  border-bottom: dashed 1px silver;
  list-style-type: none!important;
}
ul li:last-of-type {
  border-bottom: none;
}
ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f138";
  position: absolute;
  left : 0.5em; 
  color: #ffb03f; 
}
ul li:after {
  background: #ffb03f;
  color: #fff;
  font-weight: bold;
  position: absolute;
  left: -2px;
  bottom: 100%;
  padding: 1px 7px;
  content: "POINT";
  letter-spacing: 0.05em;
}
```
</details>

![style ul ol li với css](./4-a-list-ul-ol-style.png 'List style - Template 33')

---
<details><summary>Code CSS - Mẫu 34</summary>

```css
ul {
  border: solid 2px #ffb03f;
  padding: 0.5em 1em 0.5em 2.3em;
  position: relative;
  margin-top: 2em;
}
ul li {
  line-height: 1.5;
  padding: 0.5em 0;
  list-style-type: none!important;
}
ul li:before {
  font-family: "Font Awesome 5 Free";
  content: "\f00c";
  position: absolute;
  left : 1em;
  color: #ffb03f; 
}
ul li:after {
  background: #ffb03f;
  color: #fff;
  font-family: "Font Awesome 5 Free",'Avenir','Arial',sans-serif;
  position: absolute;
  left: -2px;
  bottom: 100%;
  padding: 1px 7px;
  content: '\f0a7  Check';
  letter-spacing: 0.05em;
}
```
</details>

![style ul ol li với css](./4-b-list-ul-ol-style.png 'List style - Template 34')

Trên đây là tổng hợp một số **mẫu định dạng thẻ `<ul>`, `<ol>` bằng css** cho trang web của bạn. Hy vọng bạn sẽ thích bộ sưu tập này!
