# Dvorak keymap for CRKBD

To flash the halves use:

```
#left side
make crkbd:fastjames:avrdude-split-left
#right side, with RGB matrix fix
make crkbd:fastjames:avrdude-split-right RGB_MATRIX_SPLIT_RIGHT=yes
```
