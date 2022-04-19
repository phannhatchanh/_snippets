---
date: 2022-04-20
title: 'useInjectScript'
description: 'Tạo một Hook để chèn file JS trong React'
category: 'React Component'
slug: 'tao-hook-de-chen-js-script-trong-react'
---

Bạn có thể sử dụng code dưới đây để chèn một file JS vào dự án React của bạn!
```js:title=./components/useInjectScript.js
import { useEffect } from "react"

export const useInjectScript = (src: string) =>
  useEffect(() => {
    // @ts-ignore
    if (window.__custom_injected__) return
    // @ts-ignore
    window.__custom_injected__ = true

    const script = document.createElement("script")
    script.src = src
    script.defer = true

    const onScriptError = () => script.remove()
    script.addEventListener("error", onScriptError)

    document.body.appendChild(script)
  }, [])
```

```js:title=./pages/index.js
import { useInjectScript } from '../components/useInjectScript'

const Component = () => {
  useInjectScript('https://phannhatchanh.com/xxx/lib.js')
  
  return (
    <>
      <h1>Hello World</h1>
    </>
  )
} 
```