---
date: 2022-03-16
title: 'Copy to Clipboard'
description: 'Cách thêm button Copy vào các code blocks bằng JavaScript'
category: 'JavaScript'
slug: 'them-nut-copy-vao-code-blocks-bang-javascript'
---

Nếu bạn đang chia sẻ những ý tưởng của bạn bằng những đoạn code được đăng tải trên web của bạn thì việc thêm một button Copy to Clipboard vào các Code Blocks là cần thiết, nó giúp cho khách truy cập có thể dễ dàng sao chép và kiểm thử nếu khi cần.

Bại có thể xem demo trước [tại đây](../../../demo/copy-to-clipboard/) hoặc bạn cũng có thể thấy nó hoạt động ngay trên trang này.

Cấu trúc HTML cuối cùng sẽ có dạng như sau:
```html
<div class="highlight">
  <code> ... </code>
  <button>Copy</button>
</div>
```

Với đoạn HTML trên bạn có thể thấy trong thẻ `<div class="highlight">` có 2 phần tử con. Phần tử con đầu tiên là thẻ `<code>` và phần tử con thứ hai vào đó là thẻ `<button>` sẽ được thêm vào bằng đoạn code dưới đây:

```js
// get the list of all highlight code blocks
const highlights = document.querySelectorAll('div.highlight');
// add the copy button to each code block
highlights.forEach(div => {
  // create the copy button
  const copy = document.createElement('button');
  copy.innerHTML = 'Copy';
  // add the event listener to each click
  copy.addEventListener('click', handleCopyClick);
  // append the copy button to each code block
  div.append(copy);
});
```

Thêm một ít CSS để làm cho nút Copy đẹp hơn một chút. Đoạn CSS dưới đây sẽ đặt nút Copy ở góc phải phía trên.
```css
div.highlight button {
  color: #adb5bd;
  box-sizing: border-box;
  transition: 0.2s ease-out;
  cursor: pointer;
  user-select: none;
  background: rgba(0, 0, 0, 0.15);
  border: 1px solid rgba(0, 0, 0, 0);
  padding: 5px 10px;
  font-size: 0.8em;
  position: absolute;
  top: 0;
  right: 0;
  border-radius: 0 0.15rem;
}
```

Tiếp theo là Copy code vào clipboard. Để làm điều này, bạn có thể sử dụng [clipboard API](https://developer.mozilla.org/en-US/docs/Web/API/Clipboard_API) nhưng tiếc là nó chỉ hoạt động trên các trình duyệt hiện đại. Bạn có thể sử dụng đoạn mã dưới đây đi kèm theo các comments sẽ giúp bạn dễ dàng hiểu được cách thức hoạt động của nó.
```js
const copyToClipboard = str => {
  const el = document.createElement('textarea'); // Create a <textarea> element
  el.value = str; // Set its value to the string that you want copied
  el.setAttribute('readonly', ''); // Make it readonly to be tamper-proof
  el.style.position = 'absolute';
  el.style.left = '-9999px'; // Move outside the screen to make it invisible
  document.body.appendChild(el); // Append the <textarea> element to the HTML document
  const selected =
    document.getSelection().rangeCount > 0 // Check if there is any content selected previously
      ? document.getSelection().getRangeAt(0) // Store selection if found
      : false; // Mark as false to know no selection existed before
  el.select(); // Select the <textarea> content
  document.execCommand('copy'); // Copy - only works as a result of a user action (e.g. click events)
  document.body.removeChild(el); // Remove the <textarea> element
  if (selected) {
    // If a selection existed before copying
    document.getSelection().removeAllRanges(); // Unselect everything on the HTML document
    document.getSelection().addRange(selected); // Restore the original selection
  }
};
```

Tiếp theo là hàm dùng để xử lí sự kiện khi click vào button Copy mà ta đã khai báo trước đó:
```js
function handleCopyClick(evt) {
  // get the children of the parent element
  const { children } = evt.target.parentElement;
  // grab the first element (we append the copy button on afterwards, so the first will be the code element)
  // destructure the innerText from the code block
  const { innerText } = Array.from(children)[0];

  // copy all of the code to the clipboard
  copyToClipboard(innerText);
  // alert to show it worked, but you can put any kind of tooltip/popup
  alert(innerText);
}
```

Và đó là tất cả những gì mà bạn cần để thêm nút buton Copy vào các code blocks trên trang web của bạn.
