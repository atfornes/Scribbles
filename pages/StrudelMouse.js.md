- let mouse;
  (function(){
    document.onmousemove = function(e){
      mouse.x = e.x;
      mouse.y = e.y;
    }
  })();