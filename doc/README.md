![KEYBOARD/4A-99](../img/logo.png)

# Documentation

This project is intended as an **upgrade** for an existing Mitsumi mylar "keyboard". As such, you will require one of these (probably non-functioning) "keyboards" to begin. 
We will be re-using all of the original keycaps, the metal PCB support strips and screws, and (optionally) the space bar support brackets and 15-pin ribbon connector.

Don't feel bad for it. That brown abomination should have been relegated to landfill years ago. It's one of the lucky ones!

## Bill of Materials

Here's the full list of items you'll need to complete this upgrade. Some of these items are optional, many are 3D printed, and some can be salvaged from your mylar monster.

| Qty  | Description                                         | Thumbnail                                    | Notes                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| :--- | :-------------------------------------------------- | :------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Mitsumi mylar TI-99/4A "keyboard"                   | ![](img/thumb/mitsumi.jpg)                   | To pillage keycaps and (optionally) other components                                                                                                                                                                                                                                                                                                                                                                                      |
| 1    | KEYBOARD/4A-99 PCB                                  | ![](img/thumb/pcb.jpg)                       | I recommend ordering it in Black. But, you do you. See [/pcb](../pcb/)                                                                                                                                                                                                                                                                                                                                                                    |
| 47   | Cherry MX compatible key switches                   | ![](img/thumb/akko-switch.jpg)               | I have tested [Akko V3 Cream Black (Amazon)](https://www.amazon.com/Akko-Keyboard-Dustproof-Mechanical-Switches/dp/B0CBK74L29). Unfortunately, they only come in 45 packs. Such is life.                                                                                                                                                                                                                                                  |
| 1    | 8mm latching button                                 | ![](img/thumb/latching-button.jpg)           | For Alpha lock. [GPBS-800L (Mouser)](https://www.mouser.com/ProductDetail/CW-Industries/GPBS-800L?qs=sajaCoHCXPRO4feefwykvw%3D%3D)                                                                                                                                                                                                                                                                                                        |
| 1    | 1N4148 Diode (Optional)                             | ![](img/thumb/1n4148.jpg)                    | Can be jumpered if you don't want the [ALPHA LOCK fix](http://www.mainbyte.com/ti99/console/alpha_lock.html)                                                                                                                                                                                                                                                                                                                              |
| 1    | 15-pin 0.1" pitch x ~75mm+ female IDC cable         | ![](img/thumb/idc-cable.jpg)                 | Can re-use cable from original "keyboard".<br>Can use new dupont cable (optionally, with a header on the PCB).<br>New parts: Can get two from a [IDSS-15-D-06.00-G-R (Mouser)](https://www.mouser.com/ProductDetail/Samtec/IDSS-15-D-06.00-G-R?qs=82jvyl5dHWdNzrTJ70gz7A%3D%3D) or one from a [IDSS-15-S-03.00-T-G-ST4 (Mouser)](https://www.mouser.com/ProductDetail/Samtec/IDSS-15-S-03.00-T-G-ST4?qs=9r4v7xj2Lnnz8e%252BG4N9S7g%3D%3D) |
| 10   | 3x8mm self-tapping<br>**OR**<br>M3x5 machine screws | ![](img/thumb/screws-selftap.jpg)            | Either [3x8mm self tapping (Amazon)](https://www.amazon.com/Oneyijun-Tapping-Mushroom-Fasteners-Drilling/dp/B096MWH691)<br>**OR**<br>[M3x5 machine screws (Amazon)](https://www.amazon.com/a16051600ux0507-Stainless-Phillips-Machine-Fasteners/dp/B01LK6YGF2) to suit brass inserts.                                                                                                                                                     |
| 10   | M3 x 5.7 x 4.6mm brass inserts (Optional)           | ![](img/thumb/brass-inserts.jpg)             | [M3 x 5.7 x 4.6 from Amazon](https://www.amazon.com/uxcell-Knurled-Printing-Threaded-Embedment/dp/B0CB8LKVYF)                                                                                                                                                                                                                                                                                                                             |
| 1    | PCB mount (left)                                    | ![](img/thumb/pcb-mount-left.jpg)            | 3D printed (self tapping or brass insert options available)                                                                                                                                                                                                                                                                                                                                                                               |
| 1    | PCB mount (right)                                   | ![](img/thumb/pcb-mount-right.jpg)           | 3D printed (self tapping or brass insert options available)                                                                                                                                                                                                                                                                                                                                                                               |
| 2    | PCB support backer                                  | ![](img/thumb/pcb-support-backer.jpg)        | 3D printed. The metal supports on the original keyboard will screw into these.                                                                                                                                                                                                                                                                                                                                                            |
| 2    | Space bar support                                   | ![](img/thumb/space-bar-support.jpg)         | 3D printed (self tapping or brass insert options available)<br>Two model options available:<br> * One to re-use Mitsumi spacebar support (pictured)<br>* Another two-piece model using all new 3D printed components                                                                                                                                                                                                                      |
| 45   | Keycap adapter (standard)                           | ![](img/thumb/keycap-adapter.jpg)            | 3D printed. 7x7 array model is also available.                                                                                                                                                                                                                                                                                                                                                                                            |
| 1    | Keycap adapter (space bar)                          | ![](img/thumb/keycap-adapter.jpg)            | 3D printed. I've found the slot in the space bar is slightly larger. It could just me mine?.                                                                                                                                                                                                                                                                                                                                              |
| 1    | Keycap adapter (right shift)                        | ![](img/thumb/keycap-adapter-rshift.jpg)     | 3D printed                                                                                                                                                                                                                                                                                                                                                                                                                                |
| 1    | Keycap adapter (alpha lock)                         | ![](img/thumb/keycap-adapter-alpha-lock.jpg) | 3D printed                                                                                                                                                                                                                                                                                                                                                                                                                                |

## 3D Printing Notes

All 3D printed models were designed using Onshape. If you need to make modifications, the project is available here: [KEYBOARD/4A-99 on Onshape](https://cad.onshape.com/documents/30d24a60e4ff53542fc4ebb4/w/1ff27c22063da5b9cb2d7645/e/a78a0ae34698a1552e1e650e)

In developing this upgrade, all items were printed using:
* **Printer:** Creality Ender-3 V3 KE
* **Nozzle:** 0.4mm
* **Filament:** 1.75mm Elegoo PLA+ (PETG would likely work very well too)
* **Layer height:** 0.15mm
* **Supports:** Yes, from bed only (except for standard keycap adapters - no supports)

### Threaded inserts

All of the models which accept screws have two versions. One which takes threaded inserts and another designed to take a self-tapping screw directly. e.g.

```
keyboard4a99-pcb-mount-left-inserts.stl
keyboard4a99-pcb-mount-left-selftap.stl
```

| Type          | Hole diameter | Notes                                                                                                                          |
| :------------ | :------------ | :----------------------------------------------------------------------------------------------------------------------------- |
| Brass inserts | 4.5mm         | [M3 x 5.7 x 4.6 from Amazon](https://www.amazon.com/uxcell-Knurled-Printing-Threaded-Embedment/dp/B0CB8LKVYF)                  |
| Self tapping  | 2.8mm         | [3mm x 8mm self tapping screws from Amazon](https://www.amazon.com/Oneyijun-Tapping-Mushroom-Fasteners-Drilling/dp/B096MWH691) |

If you require a different hole size, the Onshape project includes a global variable `#threadsize` to control this.

## Detailed procedure


### Key puller

If you need a key puller, I have used and can recommend this [TI-99 keycap puller by Darryl Hirschler on Thingiverse](https://www.thingiverse.com/thing:6565856)

![](img/key-puller.jpg)


