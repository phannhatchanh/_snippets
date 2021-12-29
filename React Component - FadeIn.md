---
date: 2021-12-20
name: 'FadeIn'
description: 'Tạo một component FadeIn đơn giản trong React'
category: 'React Component'
slug: 'fade-in'
---

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
```jsx
// Wrap whatever elements you want in a `<FadeIn>` wrapper:
<FadeIn>
  <SomeBitOfUI />
</FadeIn>

// Render conditionally to fade on every re-enter
{someBoolean && (
  <FadeIn>
    <ThingToShow />
  </FadeIn>
)}

// Customize `duration` and `delay`
<FadeIn delay={250} duration={450}>
  <p>Slightly later and longer animation</p>
</FadeIn>
```