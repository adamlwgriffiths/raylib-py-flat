# Raylib-py Flat

Wraps [Raylib-py](https://github.com/overdev/raylib-py/) and flattens the modules to a single import.

## Installation

`pip install raylib-py-flat`


## Dependencies

* [raylib-py](https://github.com/overdev/raylib-py) (using the `raylibpy-3.7` branch)


## Demo

```
import raylib as rl

def main():
    rl.init_window(800, 450, "raylib [core] example - basic window")
    rl.set_target_fps(60)

    while not rl.window_should_close():
        rl.begin_drawing()
        rl.clear_background(rl.RAYWHITE)
        rl.draw_text("Congrats! You created your first window!", 190, 200, 20, rl.LIGHTGRAY)
        rl.end_drawing()

    rl.close_window()

if __name__ == '__main__':
    main()

```
