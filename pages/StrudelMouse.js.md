- (function(){
  document.onmousemove = function(e){
  window.mouse.x = e.x;
  window.mouse.y = e.y;
  }
  })()
- let mouse = window.mouse
- sound("bd sd").lpf(mouse.x * 5)