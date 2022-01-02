---
date: 2021-12-27
title: 'Typing Effect'
description: 'Hiệu ứng máy đánh chữ với HTML và CSS (KHÔNG JavaScript!)'
category: 'HTML & CSS'
slug: 'typing-effect-voi-css'
---

Có rất nhiều thư viện Javascript với hiệu ứng kiểu máy đánh máy đẹp mắt đã được chia sẻ rất nhiều trên Internet như [React Typist](https://github.com/jstejada/react-typist), [TypeWriterJS](https://github.com/tameemsafi/typewriterjs),... Nếu bạn không muốn sử dụng nó thì dưới đây là một đoạn CSS ngắn với hiệu ứng máy đánh chữ đơn giản mà không sử dụng JavaScript.
```css
span {
  display: block;
  font-family: monospace;
  white-space: nowrap;
  border-right: 2px solid;
  width: 13ch;

  animation: typing 2s steps(13), blink .5s infinite step-end alternate;
  overflow: hidden;
}

@keyframes typing {
  from {width: 0}
}

@keyframes blink {
  50% {border-color: transparent;}
}
```

- `border-right: 2px solid;` độ rộng của con trỏ soạn thảo.
- `animation` tốc độ của hiệu ứng đánh chữ, của dấu nhấp nháy.
- `overflow: hidden;` ẩn đoạn văn bản.
- `width: 13ch;` số ký tự của đoạn văn bản.

```html
<span>Typing Effect</span>
```
