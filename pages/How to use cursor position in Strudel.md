public:: true
type:: [[Post]]
date:: [[2023-09-05]]

-
-
- You can use standard Javascript in [[Strudel]]! which enables exciting things such as [using the mouse position to control parameters]([[How to use cursor position in Strudel]]). But you have to be careful, and use single quote strings (See [here](https://strudel.tidalcycles.org/learn/code#strings) why).
  id:: 64f77d17-a23a-4040-9b11-676fd52e73dd
-
- A first attempt only let us use the value of the cursor at the time of (re)evaluation. Thus, we cannot change the parameters just by moving the cursor as in [[Hydra]]. This is however interesting to produce changes  only when desired, and not when the performer moves the cursor to change some code.
- [[StrudelMouse.js]]
  id:: 64f8dc26-7591-463d-b01a-33c5d8bea69b
- [Strudel using cursor position](https://strudel.tidalcycles.org/#Ly8gQHRpdGxlIFN0cnVkZWwgdXNpbmcgY3Vyc29yIHBvc2l0aW9uCi8vIEBieSBUQUNIQX4KLy8gQGxpY2Vuc2UgQ0MwIGh0dHBzOi8vY3JlYXRpdmVjb21tb25zLm9yZy9wdWJsaWNkb21haW4vemVyby8xLjAvCgooZnVuY3Rpb24oKXsKICBpZiAoIXdpbmRvdy5tb3VzZSkKICAgIHdpbmRvdy5tb3VzZSA9IHsKICAgICAgeDogMCwKICAgICAgeTogMAogICAgfSAgCiAgZG9jdW1lbnQub25tb3VzZW1vdmUgPSBmdW5jdGlvbihlKXsKICAgIHdpbmRvdy5tb3VzZSA9IHsKICAgICAgeDogZS54LAogICAgICB5OiBlLnkKICAgIH0KICB9Cn0pKCkKCmxldCBtb3VzZSA9IHdpbmRvdy5tb3VzZQoKc291bmQoImJkIHNkIikubHBmKG1vdXNlLnggKiA1KQo%3D)
  id:: 6516a254-30a0-4a09-bf84-1505436fad73
-