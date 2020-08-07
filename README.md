# Quackfire controller rev1

This is a replacement controller for the CM Quickfire Rapid. Everything works, except for the WinLock LED (which isn't connected to the controller).

## Building
If you feel like building a few of these PCBs yourself, go to the 'Releases' tab and download the latest gerber files. Order those at your favourite PCB manufacturer, get the components needed (see below) and solder them on! A hot air station is not required but a good soldering iron is. Flux is recommended.

## Opening the project
To open the files you will need the latest KiCAD nightly version.

## Bill of materials (BOM)
Amount is per PCB, multiply as needed.

| LCSC part # | Description             | Value | Package  | Amount |
| ----------- | ----------------------- | ----- | -------- | ------:|
| C83060      | Capacitor               | 0.1uF | 0603     | 4      |
| C131056     | Capacitor               | 4.7uF | 0805     | 1      |
| C302042     | Capacitor               | 1uF   | 0603     | 1      |
| C261942     | Fuse                    |       | 0805     | 1      |
| C98220      | Resistor                | 10K   | 0603     | 2      |
| C12028      | Resistor                | 5.1K  | 0603     | 2      |
| C384264     | Resistor                | 22    | 0603     | 2      |
| C44854      | MCU                     | 32U4  | QFP-44   | 1      |
| C341521     | Resonator               | 16MHz | SMD      | 1      |
|             | 2x10 2.00mm pin header  |       | THT      | 2      |
