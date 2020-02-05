# Reference

- [Fundamentals of Computing Specialization](https://www.coursera.org/specializations/computer-fundamentals) (IIPP + PoC), Rice, Coursera
- PyOPENGL documentation
- https://wiki.python.org/moin/PythonGames
- first read source code of many other fantastic games to get a sense

# Install

```python
'''
sudo apt-get install xxx
```

# How to play

Instructions TBD

# Demo

www.github.io/neo-mashiro/xxx

# Note

1. Limit the number of global variables, as the script size increases, global variables could make a bunch of nasty bugs that are hard to fix.
2. Build a class to keep track of the game status from multiple perspectives, wrap global variables up into fields within the class, and add methods as appropriate.

```python
'''
It's a good habit not to use public fields, the class fields should all be private.
Private fields are only visible within the class and should not be manipulated from outside.
'''

class GameState():
    def __init__(self):
        self._time = 0
        self._status = True
        self._frame_height = 600   
        self._frame_width = 800
```

