---
date: 2021-12-30
name: 'random()'
description: 'Tạo một số ngẫu nhiên trong một phạm vi nhất định theo cách mà chúng ta mong muốn.'
category: 'JavaScript'
slug: 'tao-so-ngau-nhien-trong-pham-vi-bang-javascript'
---

Trong JavaScript, ta có thể tạo các số ngẫu nhiên bằng cách sử dụng hàm `Math.random()`. Tuy nhiên, hàm này chỉ tạo ra các số ngẫu nhiên với dấu phẩy động trong khoảng từ 0 đến 1. Theo tôi, việc cần hiển thị một số nguyên ngẫu nhiên trong một phạm vi nhất định sẽ phổ biến hơn nhiều. Ví dụ: hiển thị một số ngẫu nhiên từ 10 đến 20 chẳn hạn. Đoạn code nhỏ gọn dưới đây sẽ cho giúp chúng ta làm điều đó!
```javascript
const random = (min, max) => Math.floor(Math.random() * (max - min)) + min;
```

### Cách sử dụng
```js
// Lấy một số ngẫu nhiên trong số [10, 11, 12, 13]
random(10, 14) ; 
// Lấy một số ngẫu nhiên từ 1 đến 100 (bao gồm tất cả)
random(1, 101 ) ; 
// Lấy một số ngẫu nhiên từ -10 đến 10 (bao gồm tất cả)
random(-10, 11) ; 
```

