---
date: 2021-12-20
title: 'HTML Skeleton'
description: 'Khởi động dự án tiếp theo của bạn với khung HTML'
category: 'HTML & CSS'
slug: 'html-skeleton'
---

Đây là một khung HTML đơn giản để bạn khởi động bất kỳ dự án HTML mới. Nó bao gồm tất cả các phương pháp hay nhất hiện nay để chia sẻ trên mạng xã hội.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Your Page Title</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="author" content="Your name">
  <meta name="description" content="Brief description">
  <meta property="og:title" content="Your Page Title">
  <meta property="og:description" content="Brief description">
  <meta property="og:image" content="/some-image.png">
  <meta property="og:url" content="/this-page.html">
  <meta property="og:site_name" content="Your Site Name">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image:alt" content="image description">
  <link href="style.css" rel="stylesheet">
  <link rel="icon" type="image/svg+xml" href="/favicon.svg">
</head>
<body>
  <h1>Your content here!</h1>
  <script src="script.js"></script>
</body>
</html>
```

Nếu bạn hiện đang làm việc với React bạn sẽ phải sử dụng thẻ tự đóng `<meta />` thay vì `<meta>` trong HTML. Nó không hoàn toàn cần thiết trong HTML, nhưng nó cần thiết trong JSX.
