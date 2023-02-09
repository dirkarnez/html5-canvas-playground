[html5-canvas-playground](https://dirkarnez.github.io/html5-canvas-playground/)
===============================================================================
Run on SPA server
### Content
- [clock-face](https://dirkarnez.github.io/html5-canvas-playground/clock-face/index.html)
- [image-drawing](https://dirkarnez.github.io/html5-canvas-playground/image-drawing/index.html)

### Notes
- Math issues
  - [Javascript Math.cos and Math.sin are inaccurate. Is there any solution? - Stack Overflow](https://stackoverflow.com/questions/6223616/javascript-math-cos-and-math-sin-are-inaccurate-is-there-any-solution)
- Blurry canvas
  - Solutions
    1. [jondavidjohn/hidpi-canvas-polyfill: A JavaScript drop-in module to polyfill consistent and automatic HiDPI Canvas support.](https://github.com/jondavidjohn/hidpi-canvas-polyfill)
        - [高清屏中 Canvas 的绘制 | Deng's Blog](http://objcer.com/2017/10/10/High-DPI-Canvas-Render/)
          - [YingshanDeng/hidpi-canvas-polyfill: A JavaScript drop-in module to polyfill consistent and automatic HiDPI Canvas support.](https://github.com/YingshanDeng/hidpi-canvas-polyfill)
        - put this in `<head>`
          - ```javascript
            <script src="https://cdn.rawgit.com/jondavidjohn/hidpi-canvas-polyfill/1.0.9/dist/hidpi-canvas.min.js"></script>
            ```
     2. [szimek/signature_pad: HTML5 canvas based smooth signature drawing](https://github.com/szimek/signature_pad)
