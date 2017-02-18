# notes to self

Python 3.7
pygame-1.9.2a0.win32-py3.2.msi

Represent the slope as a grid with the top of the slope as the top of the
screen.

When sending a drop down the slope, randomly select the start position. The
drop can go west, east, southwest, south, or southeast. In other words, it can
go anywhere but back up the slope.

    x x x
    o d o
    o o o

represent grid by numbers where a tile's number represents how
likely the drop would be to choose that tile next. The higher the number, the
more likely the drop would choose that tile next.

weight southwest, south, and southeast higher than west and east

Live JavaScript demo [here](http://eafeicke.github.io/rivulets.html)