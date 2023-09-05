- ((64f77bdc-4b4c-48ae-bb7b-a941a2f3e107))
- You can use standard Javascript in your [[Strudel]] code! which enables exciting things such as [using the mouse position to control parameters]([[How to use cursor position in Strudel]]). But you have to be careful, and use single quote strings (See [here](https://strudel.tidalcycles.org/learn/code#strings) why)
  id:: 64f77d17-a23a-4040-9b11-676fd52e73dd
-
- A first attempt only let us use the value of the cursor at the time or (re)evaluation. Thus, we cannot change the parameters just by moving the cursor. This is however interesting to only produce changes when desired, and not because the programmer moves the cursor to change some code.
- {{embed [[StrudelMouse.js]]}}
- https://strudel.tidalcycles.org/#KGZ1bmN0aW9uKCl7CmRvY3VtZW50Lm9ubW91c2Vtb3ZlID0gZnVuY3Rpb24oZSl7CiAgd2luZG93Lm1vdXNlLnggPSBlLng7CiAgd2luZG93Lm1vdXNlLnkgPSBlLnk7Cn0KfSkoKQoKbGV0IG1vdXNlID0gd2luZG93Lm1vdXNlCgpzb3VuZCgiYmQgc2QiKS5scGYobW91c2UueCAqIDUpCg%3D%3D
-