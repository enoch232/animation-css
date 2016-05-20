# animation-css
####CSS library for cool animations. This file is extremely light, and does it job very well.
Currently working animations:
* fadeInRight
* fadeOutRight
* fadeInLeft
* fadeOutLeft
* fadeInDown
* fadeOutDown
* fadeInUp
* fadeOutUp
* focus

You can add the animation by simply adding the name to the class.
Make sure you include animation speed as well.


##Animation Speed
In order to control the duration, you need to add the following into the class
* 'a-fast'      to make the animation fast (1s)
* 'a-medium'    to make the animation medium fast (2s)
* 'a-slow'      to make the animation slow (3s)


##Iteration
You can make iteration count to infinite times through adding the following to the class:
* 'a-infinite'

If you want specific iteration count, modify the css file to whatever value you want.

If you prefer more 
##Example
``` 
<div class = "a-fast fadeInRight">Hello</div>
```

