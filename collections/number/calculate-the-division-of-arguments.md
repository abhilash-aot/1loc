---
title: Calculate the division of arguments
category: Number
tags:
  - posts
layout: layouts/post.njk
---

```js
const division = (...args) => args.reduce((a, b) => a / b);

// Example
division(1, 2, 3, 4);   // 0.04166666666666666
```