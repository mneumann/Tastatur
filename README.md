# Tastatur
Project building my own mechanical keyboard

## Ideas

* Compact (~ 60 keys)
* Non-staggered, ortholinear key layout
* Detects any number of keypress-combinations (suitable for steno/shorthand)
* Each LED can be controlled independently (good for learning new typing layouts)
* USB/bluetooth connectivity
* Small LCD (matrix) display to display one line
* Serial port (directly attach to embedded devices)
* Self-powered (battery). USB-rechargeable
* Firmware written in [Rust][rust]
* (VGA connector)

## Ergonomic Ideas

* Mobile one/two-handed chord (?) keyboard.
* Uses orientation and movement to switch between different layouts
* Can be used while standing, walking etc.

## Inspiration

* [Planck Keyboard](http://olkb.com/planck)
* [Atreus Keyboard](http://atreus.technomancy.us/)

## Hardware

* [CD4067b](http://www.ti.com/lit/ds/symlink/cd4067b.pdf): 16-channel multiplexer
* Gateron Brown key switches
* [BBC micro:bit](https://www.microbit.co.uk/): 32-bit ARM© Cortex™ M0 CPU

[rust]: https://www.rust-lang.org/
