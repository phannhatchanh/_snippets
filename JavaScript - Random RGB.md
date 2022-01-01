---
date: 2021-12-20
name: 'randomRGB()'
description: 'Hàm tạo chuỗi mã màu <strong>RGB</strong> ngẫu nhiên'
category: 'JavaScript'
slug: 'random-rgb'
---

Trong một vài trường trường hợp nào đó. Nếu bạn muốn **hiển thị hệ màu RGB hoặc RGBA ngẫu nhiên** thì bạn có thể sử dụng đoạn code dưới đây trong dự án của bạn.

```javascript
const random255 = () => Math.floor(Math.random() * 255)

const randomRGB = () => {
  const r = random255()
  const g = random255()
  const b = random255()

  return `rgb(${r}, ${g}, ${b})`
}

const randomRGBA = () => {
  const r = random255()
  const g = random255()
  const b = random255()
  const a = Math.random()

  return `rgb(${r}, ${g}, ${b}, ${a})`
}
```