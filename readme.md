# Raycasting

## Description

This project is a Python implementation of raycasting, with an attempt of 3D rendering the 'casted' scene.

## Dependencies

This project uses [**Pygame**](https://www.pygame.org/news) and [**Numpy**](https://numpy.org/), both of which can be installed via *pip*, by:

```
pip install pygame
pip install numpy
```

## Drawing Mode

On Drawing mode you can use your cursor to place **obstacles** that will block the rays. To place an obstacle, simply click and hold your left mouse button (the cursor's current position will be one of the edges of the obstacle), drag it to another place and let it go.

## Controls

### Movement

- W => Move Forwards
- A => Move Left
- S => Move Backwards
- D => Move Right

### Rotation

- Left arrow key => Rotate Left
- Right arrow key => Rotate Right
- Up arrow key => Move scene up
- Down arrow key => Move scene down

### Interaction

- Q => Toggles **drawing** mode
- R => Reset scene

## Running

Finally, you can run the project by executing the _main.py_  file. For instance, by typing the following on the terminal:

```
python3 main.py
```
