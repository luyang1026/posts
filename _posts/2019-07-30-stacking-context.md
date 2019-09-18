---
layout: post
title: Stacking Order
tags: [css]
---

When the **z-index** property is not specified on any element, elements are stacked in the following order (from bottom to top):
1. the background and borders of the root element
2. Descendant **non-positioned** blocks, in order of appearance in the HTML
3. Descendant **positioned** element, in order of appearance in the HTML

The stacking context is a three-dimentional conceptualization of HTML elements along imaginary z-axis relative to the user.
