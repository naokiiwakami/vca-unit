# vca-unit

WARNING: The module is not fully tested yet!

This is a small VCA unit that works without any additional components.
The module is built so small that it is suitable to be used as a sub module in a larger
synth project. The board size is about 22mm x 10.5mm.
There are six pins on the module; two rows with 2.54mm pitch that are seven pitches apart.
You can run the module on a breadboard, too.

![board-3d-image](docs/board-3d.png)

The unit is tested with +/-12V symmetrical power supply. Basic specifications are:

- Input signal range: -8V to 8V, recommended to fit within -5V to 5V
- CV range: 0V to 8V, unity gain at about 4.6V

Following is a simple usage of the unit.

<img src="docs/example/images/example.svg" alt="vca-unit-usage" width="100%" />

This repository provides KiCAD project, symbol, and footprint of the unit.

The following is the schematics of the unit. No trimming is required for assembly.
<img src="docs/vca-unit.svg" alt="vca-unit-schematic" width="100%" />
