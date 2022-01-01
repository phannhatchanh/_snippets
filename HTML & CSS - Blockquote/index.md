---
date: 2021-12-31
name: 'blockquote'
description: 'Tổng hợp một số mẫu thiết kế với CSS cho khối <strong>blockquote</strong> đẹp.'
category: 'HTML & CSS'
slug: 'reference-blockquote'
---

Dưới đây là một số mẫu blockquote được thiết kế với HTML và CSS (không sử dụng hình ảnh), bạn có thể thay đổi style thiết kế dễ dàng. Nếu bạn có một trang blog hoặc trang web, hãy tham khảo một số mẫu dưới đây và sử dụng nó trên trang blog hay trang web của bạn.

## HTML
Đầu tiên ta sẽ có mã cho trang HTML như dưới đây (thẻ `<cite>` là một thẻ được sử dụng để chỉ ra nguồn của trích dẫn bạn có thể xóa nó nếu không muốn sử dụng)
```html
<blockquote>
  <p>CSS Block Quotation Examples</p>
  <p>Write the sentence to quote here.</p>
  <cite>Author</cite>
</blockquote>
```

## CSS

<details><summary>Code CSS - Mẫu 1</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 30px 15px 8px 15px;
    box-sizing: border-box;
    font-style: italic;
    background: #efefef;
    color: #555;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 13px;
    left: 15px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #cfcfcf;
    font-size: 28px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng FontAwesome
```css
blockquote {
    position: relative;
    padding: 30px 15px 8px 15px;
    box-sizing: border-box;
    font-style: italic;
    background: #efefef;
    color: #555;
}
blockquote:before{
    display: inline-block;
    position: absolute;
    top: 5px;
    left: 3px;
    content: "“";
    font-family: sans-serif;
    color: #cfcfcf;
    font-size: 90px;
    line-height: 1;
}
blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-1.png 'Blockquote CSS - Mẫu 1')

---
<details><summary>Code CSS - Mẫu 2</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 60px;
    box-sizing: border-box;
    font-style: italic;
    background: #efefef;
    color: #555;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 18px;
    left: 15px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #cfcfcf;
    font-size: 30px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 50px;
    box-sizing: border-box;
    font-style: italic;
    background: #efefef;
    color: #555;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 10px;
    left: -3px;
    content: "“";
    font-family: sans-serif;
    color: #cfcfcf;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-2.png 'Blockquote CSS - Mẫu 2')

---
<details><summary>Code CSS - Mẫu 3</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 35px 15px 10px 15px;
    box-sizing: border-box;
    font-style: italic;
    background: #f5f5f5;
    color: #777777;
    border-left: 4px solid #9dd4ff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.14);
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 10px;
    left: 15px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #9dd4ff;
    font-size: 28px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 7px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 35px 15px 10px 15px;
    box-sizing: border-box;
    font-style: italic;
    background: #f5f5f5;
    color: #777777;
    border-left: 4px solid #9dd4ff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.14);
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 5px;
    left: 3px;
    content: "“";
    font-family: sans-serif;
    color: #9dd4ff;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    padding: 0;
    margin: 7px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-3.png 'Blockquote CSS - Mẫu 3')

---
<details><summary>Code CSS - Mẫu 4</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 60px;
    box-sizing: border-box;
    font-style: italic;
    background: #f5f5f5;
    color: #777777;
    border-left: 4px solid #9dd4ff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.14);
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 15px;
    left: 15px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #9dd4ff;
    font-size: 30px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 7px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 60px;
    box-sizing: border-box;
    font-style: italic;
    background: #f5f5f5;
    color: #777777;
    border-left: 4px solid #9dd4ff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.14);
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 7px;
    left: 0;
    content: "“";
    font-family: sans-serif;
    color: #9dd4ff;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    padding: 0;
    margin: 7px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-4.png 'Blockquote CSS - Mẫu 4')

---
<details><summary>Code CSS - Mẫu 5</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 50px;
    box-sizing: border-box;
    font-style: italic;
    border: solid 2px #464646;
    color: #464646;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 20px;
    left: 15px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #77c0c9;
    font-size: 25px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 50px;
    box-sizing: border-box;
    font-style: italic;
    border: solid 2px #464646;
    color: #464646;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 10px;
    left: 0;
    content: "“";
    font-family: sans-serif;
    color: #77c0c9;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-5.png 'Blockquote CSS - Mẫu 5')

---
<details><summary>Code CSS - Mẫu 6</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 50px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #c2e8ed;
    font-weight: bold;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 17px;
    left: 11px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #77c0c9;
    font-size: 30px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 50px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #c2e8ed;
    font-weight: bold;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 12px;
    left: 0px;
    content: "“";
    font-family: sans-serif;
    color: #77c0c9;
    font-size: 70px;
    line-height: 1;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-6.png 'Blockquote CSS - Mẫu 6')

---
<details><summary>Code CSS - Mẫu 7</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 50px;
    box-sizing: border-box;
    font-style: italic;
    font-weight: bold;
    color: #464646;
    background: #c2e8ed;
    border: solid 3px #77c0c9;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 17px;
    left: 11px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #77c0c9;
    font-size: 30px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 15px 10px 50px;
    box-sizing: border-box;
    font-style: italic;
    font-weight: bold;
    color: #464646;
    background: #c2e8ed;
    border: solid 3px #77c0c9;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 12px;
    left: 0;
    content: "“";
    font-family: sans-serif;
    color: #77c0c9;
    font-size: 70px;
    line-height: 1;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-7.png 'Blockquote CSS - Mẫu 7')

---
<details><summary>Code CSS - Mẫu 8</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 8px 15px;
    margin: 2.5em;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #ddeaff;
    font-weight: bold;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: -30px;
    left: 11px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #ddeaff;
    font-size: 35px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 8px 15px;
    margin: 2.5em;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #ddeaff;
    font-weight: bold;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: -35px;
    left: 0px;
    content: "“";
    font-family: sans-serif;
    color: #ddeaff;
    font-size: 90px;
    line-height: 1;
}
blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-8.png 'Blockquote CSS - Mẫu 8')

---
<details><summary>Code CSS - Mẫu 9</summary>

- Sử dụng FontAwesome 
```css
blockquote {
position: relative;
    padding: 40px 10px 10px 15px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #ddeaff;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 13px;
    left: 17px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 35px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 40px 10px 10px 15px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #ddeaff;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 10px;
    left: 0px;
    content: "“";
    font-family: sans-serif;
    color: #FFF;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-9.png 'Blockquote CSS - Mẫu 9')

---
<details><summary>Code CSS - Mẫu 10</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 10px 10px 32px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #e0e0e0;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: 0;
    content: "\f10d";
    font-family: FontAwesome;
    color: #e0e0e0;
    font-size: 22px;
    line-height: 1;
    z-index: 2;
    font-weight: 900;
}

blockquote:after{
    position: absolute;
    content: '';
    left: 0;
    top: 0;
    border-width: 0 0 40px 40px;
    border-style: solid;
    border-color: transparent #ffffff;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 10px 10px 32px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #e0e0e0;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: -6px;
    left: -15px;
    content: "“";
    font-family: sans-serif;
    color: #e0e0e0;
    font-size: 70px;
    line-height: 1;
    z-index: 2;
}

blockquote:after{
    position: absolute;
    content: '';
    left: 0;
    top: 0;
    border-width: 0 0 40px 40px;
    border-style: solid;
    border-color: transparent #ffffff;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-10.png 'Blockquote CSS - Mẫu 10')

---
<details><summary>Code CSS - Mẫu 11</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 7px 16px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    border: solid 3px #72ccf4;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: -20px;
    left: -20px;
    width: 40px;
    height: 40px;
    line-height: 40px;
    border-radius: 50%;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    background: #72ccf4;
    color: #FFF;
    font-size: 22px;
    font-weight: 900;
}

blockquote:after{
    display: inline-block;
    position: absolute;
    bottom: -20px;
    right: -20px;
    width: 40px;
    height: 40px;
    line-height: 40px;
    border-radius: 50%;
    text-align: center;
    content: "\f10e";
    font-family: FontAwesome;
    background: #72ccf4;
    color: #FFF;
    font-size: 22px;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-11.png 'Blockquote CSS - Mẫu 11')

---
<details><summary>Code CSS - Mẫu 12</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 7px 16px;
    box-sizing: border-box;
    font-style: italic;
    color: #585858;
    border: solid 3px #585858;
}
blockquote:before{
    display: inline-block;
    position: absolute;
    top: -20px;
    left: -20px;
    width: 40px;
    height: 40px;
    line-height: 40px;
    border-radius: 50%;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    background: #585858;
    color: #FFF;
    font-size: 22px;
}

blockquote:after{
    display: inline-block;
    position: absolute;
    bottom: -20px;
    right: -20px;
    width: 40px;
    height: 40px;
    line-height: 40px;
    border-radius: 50%;
    text-align: center;
    content: "\f10e";
    font-family: FontAwesome;
    background: #585858;
    color: #FFF;
    font-size: 22px;
    font-weight: 900;
}

blockquote p {
    padding: 0;
    margin: 10px 0;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-12.png 'Blockquote CSS - Mẫu 12')

---
<details><summary>Code CSS - Mẫu 13</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 12px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    border: solid 3px #3ca5d4;
    border-left-width: 50px;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 50%;
    left: -37px;
    -ms-transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 22px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 12px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    border: solid 3px #3ca5d4;
    border-left-width: 50px;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 50%;
    left: -55px;
    -ms-transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    content: "“";
    font-family: sans-serif;
    color: #FFF;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-13.png 'Blockquote CSS - Mẫu 13')

---
<details><summary>Code CSS - Mẫu 14</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 12px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    border-left: solid 50px #3ca5d4;
    background: #e0f5ff;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 50%;
    left: -37px;
    -ms-transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 22px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 12px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    border-left: solid 50px #3ca5d4;
    background: #e0f5ff;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 50%;
    left: -55px;
    -ms-transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    content: "“";
    font-family: sans-serif;
    color: #FFF;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-14.png 'Blockquote CSS - Mẫu 14')

---
<details><summary>Code CSS - Mẫu 15</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 12px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    border-left: solid 40px #c4c4c4;
    background: #f3f3f3;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.19);
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 50%;
    left: -32px;
    -ms-transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 22px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 12px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    border-left: solid 40px #c4c4c4;
    background: #f3f3f3;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.19);
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 50%;
    left: -48px;
    -ms-transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    content: "“";
    font-family: sans-serif;
    color: #FFF;
    font-size: 80px;
    line-height: 1;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-15.png 'Blockquote CSS - Mẫu 15')

---
<details><summary>Code CSS - Mẫu 16</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 25px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    border: solid 3px #72ccf4;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: 0;
    width: 35px;
    height: 35px;
    border-radius: 0 0 30px;
    content: "\f10d";
    font-family: FontAwesome;
    background: #72ccf4;
    color: #FFF;
    font-size: 22px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-16.png 'Blockquote CSS - Mẫu 16')

---
<details><summary>Code CSS - Mẫu 17</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 5px 12px 5px 56px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #fff4db;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 50%;
    left: 10px;
    width: 36px;
    height: 36px;
    -ms-transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 20px;
    line-height: 36px;
    background: #ffd596;
    border-radius: 50%;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-17.png 'Blockquote CSS - Mẫu 17')

---
<details><summary>Code CSS - Mẫu 18</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 5px 12px 5px 56px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #fff0f0;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 50%;
    left: 10px;
    width: 36px;
    height: 36px;
    -ms-transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 20px;
    line-height: 36px;
    background: #ff9d9d;
    border-radius: 50%;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-18.png 'Blockquote CSS - Mẫu 18')

---
<details><summary>Code CSS - Mẫu 19</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 5px 12px 5px 56px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #f0f7ff;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 50%;
    left: 10px;
    width: 36px;
    height: 36px;
    -ms-transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 20px;
    line-height: 36px;
    background: #a5d7ff;
    border-radius: 50%;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-19.png 'Blockquote CSS - Mẫu 19')

---
<details><summary>Code CSS - Mẫu 20</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 0px 10px 5px 40px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #fff4db;
    border-top: solid 3px #ffd596;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: 0;
    width: 32px;
    height: 30px;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 18px;
    line-height: 30px;
    background: #ffd596;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-20.png 'Blockquote CSS - Mẫu 20')

---
<details><summary>Code CSS - Mẫu 21</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 0px 10px 5px 40px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #fff0f0;
    border-top: solid 3px #ff9d9d;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: 0;
    width: 32px;
    height: 30px;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 18px;
    line-height: 30px;
    background: #ff9d9d;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-21.png 'Blockquote CSS - Mẫu 21')

---
<details><summary>Code CSS - Mẫu 22</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 0px 10px 5px 40px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #f0f7ff;
    border-top: solid 3px #a5d7ff;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: 0;
    width: 32px;
    height: 30px;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 18px;
    line-height: 30px;
    background: #a5d7ff;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-22.png 'Blockquote CSS - Mẫu 22')

---
<details><summary>Code CSS - Mẫu 23</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 5px 15px 5px 55px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #f5f5f5;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: 8px;
    width: 38px;
    height: 30px;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 18px;
    line-height: 30px;
    background: #ff785b;
    font-weight: 900;
}

blockquote:after{
    content: '';
    position: absolute;
    left: 8px;
    top: 30px;
    height: 0;
    width: 0;
    border-left: 19px solid #ff785b;
    border-right: 19px solid #ff785b;
    border-bottom: 10px solid transparent;
}
.quote23 blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-23.png 'Blockquote CSS - Mẫu 23')

---
<details><summary>Code CSS - Mẫu 24</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 5px 15px 5px 55px;
    box-sizing: border-box;
    font-style: italic;
    color: #464646;
    background: #e8efff;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: 8px;
    width: 38px;
    height: 30px;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 18px;
    line-height: 30px;
    background: #87a4e3;
    font-weight: 900;
}

blockquote:after{
    content: '';
    position: absolute;
    left: 8px;
    top: 30px;
    height: 0;
    width: 0;
    border-left: 19px solid #87a4e3;
    border-right: 19px solid #87a4e3;
    border-bottom: 10px solid transparent;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-24.png 'Blockquote CSS - Mẫu 24')

---
<details><summary>Code CSS - Mẫu 25</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 5px 10px 5px 32px;
    box-sizing: border-box;
    font-style: italic;
    background: #ffebcd;
    border-bottom: solid 3px #ffbe5d;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 10px;
    left: -15px;
    width: 40px;
    height: 30px;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 18px;
    line-height: 30px;
    background: #ffbe5d;
    font-weight: 900;
}

blockquote:after{
    position: absolute;
    content: '';
    top: 40px;
    left: -15px;
    border: none;
    border-bottom: solid 8px transparent;
    border-right: solid 15px #daaa64;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-25.png 'Blockquote CSS - Mẫu 25')

---
<details><summary>Code CSS - Mẫu 26</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 5px 10px 5px 32px;
    box-sizing: border-box;
    font-style: italic;
    background: #f3f3f3;
    box-shadow: 0 3px 4px rgba(0, 0, 0, 0.15);
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 10px;
    left: -15px;
    width: 40px;
    height: 30px;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 18px;
    line-height: 30px;
    background: #92d4ff;
    box-shadow: 0 2px 2px rgba(26, 26, 26, 0.14);
    font-weight: 900;
}

blockquote:after{
    position: absolute;
    content: '';
    top: 40px;
    left: -15px;
    border: none;
    border-bottom: solid 8px transparent;
    border-right: solid 15px #6eb3e0;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-26.png 'Blockquote CSS - Mẫu 26')

---
<details><summary>Code CSS - Mẫu 27</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 15px 10px 5px;
    box-sizing: border-box;
    font-style: italic;
    background: #f3f3f3;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: -8px;
    left: 9px;
    width: 40px;
    height: 30px;
    text-align: center;
    content: "\f10d";
    font-family: FontAwesome;
    color: #FFF;
    font-size: 18px;
    line-height: 30px;
    background: #6fcdd9;
    font-weight: 900;
}

blockquote:after{
    position: absolute;
    content: '';
    top: -8px;
    left: 49px;
    border: none;
    border-bottom: solid 8px #6cacb5;
    border-right: solid 9px transparent;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-27.png 'Blockquote CSS - Mẫu 27')

---
<details><summary>Code CSS - Mẫu 28</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 20px;
    box-sizing: border-box;
    font-style: italic;
    color: #4e4e4e;
    background: #fff3e1;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 7px;
    left: 10px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #ffe2b8;
    font-size: 58px;
    line-height: 1;
    font-weight: 900;
}

blockquote:after{
    display: inline-block;
    position: absolute;
    bottom: 5px;
    right: 15px;
    text-align: center;
    content: "\f10e";
    font-family: FontAwesome;
    color: #ffe2b8;
    font-size: 40px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    position: relative;
    z-index: 3;
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 20px;
    box-sizing: border-box;
    font-style: italic;
    color: #4e4e4e;
    background: #fff3e1;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: -10px;
    content: "“";
    font-family: sans-serif;
    color: #ffe2b8;
    font-size: 130px;
    line-height: 1;
}

blockquote:after{
    display: inline-block;
    position: absolute;
    bottom: -40px;
    right: 20px;
    text-align: center;
    content: "”";
    font-family: sans-serif;
    color: #ffe2b8;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    position: relative;
    z-index: 3;
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-28.png 'Blockquote CSS - Mẫu 28')

---
<details><summary>Code CSS - Mẫu 29</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 20px;
    box-sizing: border-box;
    font-style: italic;
    color: #4e4e4e;
    background: #fff0f0;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 7px;
    left: 10px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #ffdfdf;
    font-size: 58px;
    line-height: 1;
    font-weight: 900;
}

blockquote:after{
    display: inline-block;
    position: absolute;
    bottom: 5px;
    right: 15px;
    text-align: center;
    content: "\f10e";
    font-family: FontAwesome;
    color: #ffdfdf;
    font-size: 40px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    position: relative;
    z-index: 3;
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 20px;
    box-sizing: border-box;
    font-style: italic;
    color: #4e4e4e;
    background: #fff0f0;
}
blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: -10px;
    content: "“";
    font-family: sans-serif;
    color: #ffdfdf;
    font-size: 130px;
    line-height: 1;
}
blockquote:after{
    display: inline-block;
    position: absolute;
    bottom: -40px;
    right: 20px;
    text-align: center;
    content: "”";
    font-family: sans-serif;
    color: #ffdfdf;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    position: relative;
    z-index: 3;
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-29.png 'Blockquote CSS - Mẫu 29')

---
<details><summary>Code CSS - Mẫu 30</summary>

- Sử dụng FontAwesome 
```css
blockquote {
    position: relative;
    padding: 10px 20px;
    box-sizing: border-box;
    font-style: italic;
    color: #4e4e4e;
    background: #f2f9ff;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 7px;
    left: 10px;
    content: "\f10d";
    font-family: FontAwesome;
    color: #d2e6ff;
    font-size: 58px;
    line-height: 1;
    font-weight: 900;
}

blockquote:after{
    display: inline-block;
    position: absolute;
    bottom: 5px;
    right: 15px;
    text-align: center;
    content: "\f10e";
    font-family: FontAwesome;
    color: #d2e6ff;
    font-size: 40px;
    line-height: 1;
    font-weight: 900;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    position: relative;
    z-index: 3;
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
- Không sử dụng Font Awesome
```css
blockquote {
    position: relative;
    padding: 10px 20px;
    box-sizing: border-box;
    font-style: italic;
    color: #4e4e4e;
    background: #f2f9ff;
}

blockquote:before{
    display: inline-block;
    position: absolute;
    top: 0;
    left: -10px;
    content: "“";
    font-family: sans-serif;
    color: #d2e6ff;
    font-size: 130px;
    line-height: 1;
}

blockquote:after{
    display: inline-block;
    position: absolute;
    bottom: -40px;
    right: 20px;
    text-align: center;
    content: "”";
    font-family: sans-serif;
    color: #d2e6ff;
    font-size: 90px;
    line-height: 1;
}

blockquote p {
    position: relative;
    padding: 0;
    margin: 10px 0;
    z-index: 3;
    line-height: 1.7;
}

blockquote cite {
    position: relative;
    z-index: 3;
    display: block;
    text-align: right;
    color: #888888;
    font-size: 0.9em;
}
```
</details>

![blockquote styles css, kieu dang blockquote css](./blockquote-styles-30.png 'Blockquote CSS - Mẫu 30')

Trên đây là tổng hợp một số **mẫu định dạng blockquote bằng css** cho trang web của bạn. Hy vọng bạn sẽ thích bộ sưu tập này!
