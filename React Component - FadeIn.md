---
date: 2021-12-20
title: 'FadeIn'
description: 'Tạo một component FadeIn đơn giản trong React'
category: 'React Component'
slug: 'fade-in'
---

**FadeIn** là một **component tiện ích** giúp bạn nhanh chóng thêm một hoạt ảnh mờ dần cho một phần tử hoặc một nhóm các phần tử.

```jsx:title=FadeIn.js
import React from 'react';
import styled, { keyframes } from 'styled-components';
const fadeIn = keyframes`
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
`;
const FadeIn = ({
  duration = 300,
  delay = 0,
  children,
  ...delegated
}) => {
  return (
    <Wrapper
      {...delegated}
      style={{
        ...(delegated.style || {}),
        animationDuration: duration + 'ms',
        animationDelay: delay + 'ms',
      }}
    >
      {children}
    </Wrapper>
  );
};
const Wrapper = styled.div`
  @media (prefers-reduced-motion: no-preference) {
    animation-name: ${fadeIn};
    animation-fill-mode: backwards;
  }
`;
export default FadeIn
```

## Cách sử dụng

- Bao bọc bất kỳ phần tử nào bạn muốn tạo hiệu ứng trong `<FadeIn>`
```jsx
<FadeIn>
  <SomeBitOfUI />
</FadeIn>
```

- Hiển thị `<FadeIn>` có điều kiện sau mỗi lần nạp lại
```jsx
{someBoolean && (
  <FadeIn>
    <ThingToShow />
  </FadeIn>
)}
```

- Tùy chỉnh `thời lượng` và` độ trễ` của hiệu ứng
```jsx
<FadeIn delay={250} duration={450}>
  <p>Slightly later and longer animation</p>
</FadeIn>
```
