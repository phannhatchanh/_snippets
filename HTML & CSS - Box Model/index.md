---
date: 2022-01-06
title: 'Box Model'
description: 'Tổng hợp các khung chứa nội dung đơn giản Box Model được thiết kế bằng CSS.'
category: 'HTML & CSS'
slug: 'mot-so-kieu-box-model-bang-css-dep'
---

Dưới đây là 30 ví dụ về **các kiểu hiển thị box model**. Bạn có thể dễ dàng tạo ra nó nếu biết HTML và CSS, còn nếu bạn không biết CSS thì bạn có thể sử dụng các mẫu được tạo sẵn bằng cách sao chép vào trang web của bạn.

Giả sử ta có đoạn HTML (sẽ được áp dụng từ kiểu 1 đến kiểu 25) như sau:
```html
<div class="box">
  <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,...</p>
</div>
```

---
<details><summary>Code CSS - Kiểu 1</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    font-weight: bold;
    border: solid 3px #000000;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-1.png 'styles boxed css - kiểu 1')

---
<details><summary>Code CSS - Kiểu 2</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    font-weight: bold;
    color: #6091d3;/*文字色*/
    background: #FFF;
    border: solid 3px #6091d3;/*線*/
    border-radius: 10px;/*角の丸み*/
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-2.png 'styles boxed css - kiểu 2')

---

<details><summary>Code CSS - Kiểu 3</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    color: #2c2c2f;
    background: #cde4ff;/*背景色*/
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-3.png 'styles boxed css - kiểu 3')

---

<details><summary>Code CSS - Kiểu 4</summary>

```css
.box {
    padding: 8px 19px;
    margin: 2em 0;
    color: #2c2c2f;
    background: #cde4ff;
    border-top: solid 5px #5989cf;
    border-bottom: solid 5px #5989cf;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-4.png 'styles boxed css - kiểu 4')

---

<details><summary>Code CSS - Kiểu 5</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    border: double 5px #4ec4d3;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-5.png 'styles boxed css - kiểu 5')

---

<details><summary>Code CSS - Kiểu 6</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    background: #f0f7ff;
    border: dashed 2px #5b8bd0;/*点線*/
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-6.png 'styles boxed css - kiểu 6')

---

<details><summary>Code CSS - Kiểu 7</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    color: #474747;
    background: whitesmoke;/*背景色*/
    border-left: double 7px #4ec4d3;/*左線*/
    border-right: double 7px #4ec4d3;/*右線*/
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-7.png 'styles boxed css - kiểu 7')

---

<details><summary>Code CSS - Kiểu 8</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    color: #232323;
    background: #fff8e8;
    border-left: solid 10px #ffc06e;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-8.png 'styles boxed css - kiểu 8')

---

<details><summary>Code CSS - Kiểu 9</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    color: #ff7d6e;
    background: #ffebe9;
    border-top: solid 10px #ff7d6e;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-9.png 'styles boxed css - kiểu 9')

---

<details><summary>Code CSS - Kiểu 10</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    color: #00BCD4;
    background: #e4fcff;
    border-top: solid 6px #1dc1d6;
    box-shadow: 0 3px 4px rgba(0, 0, 0, 0.32);
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-10.png 'styles boxed css - kiểu 10')

---

<details><summary>Code CSS - Kiểu 11</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    color: #5d627b;
    background: white;
    border-top: solid 5px #5d627b;
    box-shadow: 0 3px 5px rgba(0, 0, 0, 0.22);
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-11.png 'styles boxed css - kiểu 11')

---

<details><summary>Code CSS - Kiểu 12</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    color: #5989cf;
    background: #c6e4ff;
    border-bottom: solid 6px #aac5de;
    border-radius: 9px;
}
.box12 p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-12.png 'styles boxed css - kiểu 12')

---

<details><summary>Code CSS - Kiểu 13</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    color: #FFF;
    background: #6eb7ff;
    border-bottom: solid 6px #3f87ce;
    box-shadow: 0 3px 6px rgba(0, 0, 0, 0.25);
    border-radius: 9px;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-13.png 'styles boxed css - kiểu 13')

---

<details><summary>Code CSS - Kiểu 14</summary>

```css
.box {
    padding: 0.2em 0.5em;
    margin: 2em 0;
    background: #d6ebff;
    box-shadow: 0px 0px 0px 10px #d6ebff;
    border: dashed 2px white;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-14.png 'styles boxed css - kiểu 14')

---

<details><summary>Code CSS - Kiểu 15</summary>

```css
.box {
    padding: 0.2em 0.5em;
    margin: 2em 0;
    color: #565656;
    background: #ffeaea;
    box-shadow: 0px 0px 0px 10px #ffeaea;
    border: dashed 2px #ffc3c3;
    border-radius: 8px;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-15.png 'styles boxed css - kiểu 15')

---

<details><summary>Code CSS - Kiểu 16</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 2em 0;
    background: -webkit-repeating-linear-gradient(-45deg, #f0f8ff, #f0f8ff 3px,#e9f4ff 3px, #e9f4ff 7px);
    background: repeating-linear-gradient(-45deg, #f0f8ff, #f0f8ff 3px,#e9f4ff 3px, #e9f4ff 7px);
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-16.png 'styles boxed css - kiểu 16')

---

<details><summary>Code CSS - Kiểu 17</summary>

```css
.box{
    margin:2em 0;
    position: relative;
    padding: 0.5em 1.5em;
    border-top: solid 2px black;
    border-bottom: solid 2px black;
}
.box:before, .box:after{
    content: '';
    position: absolute;
    top: -10px;
    width: 2px;
    height: -webkit-calc(100% + 20px);
    height: calc(100% + 20px);
    background-color: black;
}
.box:before {left: 10px;}
.box:after {right: 10px;}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-17.png 'styles boxed css - kiểu 17')

---

<details><summary>Code CSS - Kiểu 18</summary>

```css
.box {
    margin:2em 0;
    position: relative;
    padding: 0.25em 1em;
    border: solid 2px #ffcb8a;
    border-radius: 3px 0 3px 0;
}
.box:before,.box:after {
    content: '';
    position: absolute;
    width:10px;
    height: 10px;
    border: solid 2px #ffcb8a;
    border-radius: 50%;
}
.box:after {
    top:-12px;
    left:-12px;
}
.box:before {
    bottom:-12px;
    right:-12px;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-18.png 'styles boxed css - kiểu 18')

---

<details><summary>Code CSS - Kiểu 19</summary>

```css
.box {
    position: relative;
    padding:0.25em 1em;
}
.box:before,.box:after{ 
    content:'';
    width: 20px;
    height: 30px;
    position: absolute;
    display: inline-block;
}
.box:before{
    border-left: solid 1px #5767bf;
    border-top: solid 1px #5767bf;
    top:0;
    left: 0;
}
.box:after{
    border-right: solid 1px #5767bf;
    border-bottom: solid 1px #5767bf;
    bottom:0;
    right: 0;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-19.png 'styles boxed css - kiểu 19')

---

<details><summary>Code CSS - Kiểu 20</summary>

```css
.box {
    position: relative;
    padding: 0.25em 1em;
    margin: 2em 0;
    top: 0;
    background: #efefef;
}
.box:before, .box:after{ 
    position: absolute;
    top: 0;
    content:'';
    width: 10px;
    height: 100%;
    display: inline-block;
    box-sizing: border-box;
}
.box:before{
    border-left: dotted 2px #15adc1;
    border-top: dotted 2px #15adc1;
    border-bottom: dotted 2px #15adc1;
    left: 0;
}
.box:after{
    border-top: dotted 2px #15adc1;
    border-right: dotted 2px #15adc1;
    border-bottom: dotted 2px #15adc1;
    right: 0;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-20.png 'styles boxed css - kiểu 20')

---

<details><summary>Code CSS - Kiểu 21</summary>

```css
.box {
    padding: 0.5em 1em;
    background: -moz-linear-gradient(#ffb03c, #ff708d);
    background: -webkit-linear-gradient(#ffb03c, #ff708d);
    background: linear-gradient(to right, #ffb03c, #ff708d);
    color: #FFF;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-21.png 'styles boxed css - kiểu 21')

---

<details><summary>Code CSS - Kiểu 22</summary>

```css
.box {
    padding: 0.5em 1em;
    margin: 1em 0;
    background: #f4f4f4;
    border-left: solid 6px #5bb7ae;
    box-shadow: 0px 2px 3px rgba(0, 0, 0, 0.33);
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-22.png 'styles boxed css - kiểu 22')

---

<details><summary>Code CSS - Kiểu 23 (có sử dụng Font Awesome 4)</summary>

```css
.box {
    position: relative;
    margin: 2em 0 2em 40px;
    padding: 8px 15px;
    background: #fff0c6;
    border-radius: 30px;
}
.box:before{font-family: FontAwesome;
    content: "\f111";
    position: absolute;
    font-size: 15px;
    left: -40px;
    bottom: 0;
    color: #fff0c6;
}
.box:after{
    font-family: FontAwesome;
    content: "\f111";
    position: absolute;
    font-size: 23px;
    left: -23px;
    bottom: 0;
    color: #fff0c6;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-23.png 'styles boxed css - kiểu 23')

---

<details><summary>Code CSS - Kiểu 24</summary>

```css
.box {
    position: relative;
    padding: 0.5em 0.7em;
    margin: 2em 0;
    background: #e6f4ff;
    color: #5c98d4;
    font-weight: bold;
}
.box:after {
    position: absolute;
    content: '';
    top: 100%;
    left: 30px;
    border: 15px solid transparent;
    border-top: 15px solid #e6f4ff;
    width: 0;
    height: 0;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-24.png 'styles boxed css - kiểu 24')

---

<details><summary>Code CSS - Kiểu 25</summary>

```css
.box {
    position: relative;
    background: #fff0cd;
    box-shadow: 0px 0px 0px 5px #fff0cd;
    border: dashed 2px white;
    padding: 0.2em 0.5em;
    color: #454545;
}
.box:after{
    position: absolute;
    content: '';
    right: -7px;
    top: -7px;
    border-width: 0 15px 15px 0;
    border-style: solid;
    border-color: #ffdb88 #fff #ffdb88;
    box-shadow: -1px 1px 1px rgba(0, 0, 0, 0.15);
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-25.png 'styles boxed css - kiểu 25')

---

<details><summary>Code CSS - Kiểu 26</summary>

```html
<div class="box">
    <span class="box-title">Lorem Ipsum</span>
    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,...</p>
</div>
```
```css
.box {
    position: relative;
    margin: 2em 0;
    padding: 0.5em 1em;
    border: solid 3px #95ccff;
    border-radius: 8px;
}
.box .box-title {
    position: absolute;
    display: inline-block;
    top: -13px;
    left: 10px;
    padding: 0 9px;
    line-height: 1;
    font-size: 19px;
    background: #FFF;
    color: #95ccff;
    font-weight: bold;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-26.png 'styles boxed css - kiểu 26')

---

<details><summary>Code CSS - Kiểu 27</summary>

```html
<div class="box">
    <span class="box-title">Lorem Ipsum</span>
    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,...</p>
</div>
```
```css
.box {
    position: relative;
    margin: 2em 0;
    padding: 0.5em 1em;
    border: solid 3px #62c1ce;
}
.box .box-title {
    position: absolute;
    display: inline-block;
    top: -27px;
    left: -3px;
    padding: 0 9px;
    height: 25px;
    line-height: 25px;
    font-size: 17px;
    background: #62c1ce;
    color: #ffffff;
    font-weight: bold;
    border-radius: 5px 5px 0 0;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-27.png 'styles boxed css - kiểu 27')

---

<details><summary>Code CSS - Kiểu 28</summary>

```html
<div class="box">
    <span class="box-title">Lorem Ipsum</span>
    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,...</p>
</div>
```
```css
.box {
    position: relative;
    margin: 2em 0;
    padding: 25px 10px 7px;
    border: solid 2px #FFC107;
}
.box .box-title {
    position: absolute;
    display: inline-block;
    top: -2px;
    left: -2px;
    padding: 0 9px;
    height: 25px;
    line-height: 25px;
    font-size: 17px;
    background: #FFC107;
    color: #ffffff;
    font-weight: bold;
}
.box p {
    margin: 0; 
    padding: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-28.png 'styles boxed css - kiểu 28')

---

<details><summary>Code CSS - Kiểu 29</summary>

```html
<div class="box">
  <div class="box-title">Lorem Ipsum</div>
  <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,...</p>
</div>
```
```css
.box {
    margin: 2em 0;
    background: #dcefff;
}
.box .box-title {
    font-size: 1.2em;
    background: #5fb3f5;
    padding: 4px;
    text-align: center;
    color: #FFF;
    font-weight: bold;
    letter-spacing: 0.05em;
}
.box p {
    padding: 15px 20px;
    margin: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-29.png 'styles boxed css - kiểu 29')

---

<details><summary>Code CSS - Kiểu 30</summary>

```html
<div class="box">
  <div class="box-title">Lorem Ipsum</div>
  <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,...</p>
</div>
```
```css
.box30 {
    margin: 2em 0;
    background: #f1f1f1;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.22);
}
.box .box-title {
    font-size: 1.2em;
    background: #5fc2f5;
    padding: 4px;
    text-align: center;
    color: #FFF;
    font-weight: bold;
    letter-spacing: 0.05em;
}
.box p {
    padding: 15px 20px;
    margin: 0;
}
```
</details>

![styles boxed design css](./reference-styles-box-css-30.png 'styles boxed css - kiểu 30')

