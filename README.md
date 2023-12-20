# Backroads

## Smooth Scroll
用 Tailwind 添加`<html>`标签的样式：
```css
@layer base {
  html {
    scroll-behavior: smooth;
  }
  .section {
    /* Navbar Height */
    scroll-margin-top: 4rem;
  }
}
```