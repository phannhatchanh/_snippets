---
date: 2021-12-29
name: 'randomRGB()'
description: 'Hàm tạo chuỗi rgb() ngẫu nhiên'
category: 'JavaScript'
slug: 'random-rgb'
---

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