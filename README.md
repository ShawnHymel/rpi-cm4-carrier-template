# Raspberry Pi Compute Module 4 (CM4) Carrier Template

![Rendered example of RPi CM4 Carrier Template PCB](https://raw.githubusercontent.com/ShawnHymel/rpi-cm4-carrier-template/main/images/rpi-cm4-carrier-template-rendered.png)

A template to help you design your own Raspbeery Pi Compute Module 4 carrier board (or daughterboard). The template comes with the CM4 KiCad library and gives an initial placement of Hirose connectors.

Note that a board outline has been added to be the exact size and shape of the CM4 board. This allows you to keep a neat stackup on your carrier board. However, feel free to mvoe/delete the board outline if you wish to make the carrier board extend beyond the edges of the CM4 (e.g. you wish to add a PCIe connector).

**IMPORTANT!** This project require KiCad 6. As KiCad 6 is not out yet, you will need to install a [nightly build of KiCad](https://kicad-downloads.s3.cern.ch/index.html?prefix=windows/nightly/). As a result, you may find bugs in the pre-release of v6.0. Things seem to be working with the 2020-10-29 build for me.

This project uses the CM4 library parts from the IO board KiCad files ([found here](http://datasheets.raspberrypi.org/cm4io/CM4IO-KiCAD.zip)).

## License

License TBD. It will probably be CC BY-SA 4.0. Waiting to hear what Raspberry Pi Foundation says about the license of the CM4IO files. [Question posed to forum here](https://www.raspberrypi.org/forums/viewtopic.php?t=289587).
