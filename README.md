# LED Driver Board
This simple PCB is an LM317 Adjustable Regulator in a constant current configuration. The ouput current is set by the resistor value of R1. The LM317 will adjust the current to try and maintain a constant voltage approximately 1.25V on the adjust pin, so together with Ohm's Law the current can be expressed as Iout=(Vout-Vadj)/R1, or more simply Iout=1.25/R1. The mounting holes are connected to ground and the exposed pad for the regulator is connected to Vadj and acts as a thermal relief for the regulator under high loads. Refer to the datasheet for more information on the ratings for the LM317 adjustabele regulator.

![BoardPreview](https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/2ef504c831febf3b676ea4ab92a8fa43.png)
![BottomBoard](https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/a0ea877094206880bce0eb705abeebe7.png)
