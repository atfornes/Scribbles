- ```javascript
  // @title Strudel using cursor position
  // @by TACHA~
  // @license CC0 [Creative Commons — CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
  
  (function(){
    if (!window.mouse)
      window.mouse = {
        x: 0,
        y: 0
      }  
    document.onmousemove = function(e){
      window.mouse = {
        x: e.x,
        y: e.y
      }
    }
  })()
  
  let mouse = window.mouse
  
  sound("bd sd").lpf(mouse.x * 5)
  ```