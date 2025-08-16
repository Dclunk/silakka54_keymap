# Silakka 54 keymap

Basic keymap for silakka 54 split keyboard. Meant for use in Vial.
This is far from finished, and is only my first attempt at a keymap. There are some issues I am facing in Github issues.

![Keyboard](images/silakka54.jpeg)

## Layers

### Layer 0

Layer 0 is the alpha layer, based on QWERTY.

![Layer 0](images/silakka54_layer0.png)

### Layer 1

Layer 1 has all the function keys, as well as some punctuation that is missing. On the left side, there is mostly programming punctuation (e.g. brackets). The right side has a few other punctuation keys missing. This layer is activated by pressing MO(1) on layer 0.

![Layer 1](images/silakka54_layer1.png)

### Layer 2

Layer 2 is the nav layer, including arrow keys, delete, and media keys. The naviagation is based on Vim motions. This layer is activated by pressing MO(1), the middle button on the left thumb cluster, with the RCtrl, the middle button on the right thumb cluster.

![Layer 2](images/silakka54_layer2.png)

## Notes

- There are a few clunky things currently with this layout.
    - To change the horizontal size of windows with PaperWM, I need to press both LGui and MO(1), then press J or I to shrink or grow screen.
    - To press Control+Shift, there is a tap dance TD(0) on the first layer. This is RAlt, unless I tap then hold. Then it becomes Control+Shift, which I use mostly for moving around tabs and windows in my terminal.
