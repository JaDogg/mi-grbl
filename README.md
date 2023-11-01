# grbl-1-1h-servo -- based on https://github.com/lavolpecheprogramma/grbl-1-1h-servo


This is a special version of [grbl 1.1h version](https://github.com/gnea/grbl/releases/tag/v1.1h.20190825) with servo support.

I only merge the changes done by DWiskow in [this repository](https://github.com/DWiskow/grbl1-1g-Servo) with grbl 1.1h version.

[DWiskow](https://github.com/DWiskow) explain his work in [this post](https://forum.eleksmaker.com/topic/2510/grbl-1-1g-with-servo-for-mana-se) and i replicate it in 1.1h release.

To move the servo:
```
M3 S255     (turn servo full on)
M5          (turn servo off)
M3 S125     (turn servo half way)
M3 S0       (turn servo on full off - similar to M5)
```

I have already defined all variables that allow you to use this version of grbl with a pen plotter, allowing you to make homing cycles on the X and the Y axis.

For more information about configuring grbl you can read the [official wiki](https://github.com/gnea/grbl/wiki) 

Thanks to all these guys that make this work. I don't have credits for it! ❤️

-------------

