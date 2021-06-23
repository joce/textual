# Textual

Textual is a TUI (Text User Interface) framework for Python using [Rich](https://github.com/willmcgugan/rich) as a renderer.

The end goal is to be able to rapidly create *rich* terminal applications that look as good as possible (within the restrictions imposed by a terminal emulator).

Rich TUI will integrate tightly with its parent project, Rich. Any of the existing *renderables* can be used in a more dynamic application.

This project is currently a work in progress and may not be usable for a while. Follow [@willmcgugan](https://twitter.com/willmcgugan) for progress updates, or post in Discussions if you have any requests / suggestions. 

![screenshot](./imgs/rich-tui.png)


## Updates

I'll be documenting progress in video form.

### Update 1 - Basic scrolling

[![Textual update 1](https://yt-embed.herokuapp.com/embed?v=zNW7U36GHlU&img=0)](http://www.youtube.com/watch?v=zNW7U36GHlU)

### Update 2 - Keyboard toggle

[![Textual update 2](https://yt-embed.herokuapp.com/embed?v=bTYeFOVNXDI&img=0)](http://www.youtube.com/watch?v=bTYeFOVNXDI)

### Update 3 - New scrollbars, and smooth scrolling

[![Textual update 3](https://yt-embed.herokuapp.com/embed?v=4LVl3ClrXIs&img=0)](http://www.youtube.com/watch?v=4LVl3ClrXIs)

### Update 4 - Animation system with easing function

Now with a system to animate a value to another value. Here applied to the scroll position. The animation system supports CSS like *easing functions*. You may be able to tell from the video that the page up / down keys cause the window to first speed up and then slow down.

[![Textual update 4](https://yt-embed.herokuapp.com/embed?v=k2VwOp1YbSk&img=0)](http://www.youtube.com/watch?v=k2VwOp1YbSk)
