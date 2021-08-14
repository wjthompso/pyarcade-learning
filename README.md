# pyarcade-learning
This is to learn how to use arcade

Here is the tutorial: https://realpython.com/arcade-python-game-framework/

Here's the attached github repo: https://github.com/realpython/materials/tree/master/arcade-a-primer

Some more documentation, although it doesn't list out what each function does as explicitly as the next link: https://learn.arcade.academy/en/latest/chapters/18_window_class/window_class.html

arcade function documentation: https://api.arcade.academy/en/latest/arcade.html#arcade.Window

The full game from the tutorial is in arcade_game.py.

You can't use arcade.schedule() to play sounds. It'll place once, and then the game crashes if arcade.schedule tries to play the sound again.

"During the built-in game loop, arcade calls a set of Window methods to implement all of the functionality listed above. The names of these methods all begin with on_ and can be thought of as task or event handlers. When the arcade game loop needs to update the state of all Python game objects, it calls .on_update(). When it needs to check for mouse movement, it calls .on_mouse_motion()."