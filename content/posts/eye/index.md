---
title: Insights Through Vision-Tracking Eyes Using OpenCV for Blink Detection
description: Case Study and effecient solution on blink detection
date: 2023-07-14
draft: false
slug: /cv/eye
tags:
  - eye-detection
  - python
  - opencv
---

[Published on HackerNoon](https://hackernoon.com/insights-through-vision-tracking-eyes-using-opencv-for-blink-detection)

Card layout where the card itself isn't an anchor link, but the whole card is clickable (with a `:before` pseudo element on the main `<a>`). Links inside of the card are still clickable.

## CSS

```css
.grid__item {
  &:hover,
  &:focus-within {
    background-color: #eee;
  }

  a {
    position: relative;
    z-index: 1;
  }

  h2 {
    a {
      position: static;

      &:hover,
      &:focus {
        color: blue;
      }

      &:before {
        content: '';
        display: block;
        position: absolute;
        z-index: 0;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        transition: background-color 0.1s ease-out;
        background-color: transparent;
      }
    }
  }
}
```
