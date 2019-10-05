
Components:

* Microcontroller

    * Unknown. Hidden under an unremovable blob (probably with unpackaged die underneath)
    * I2C interface to program the thing?

* XinCore F40A-104GIP

    * EN25F40A 
    * datasheet
    * 4Mbit serial flash, standard/dual/quad, 104MHz
    * $1.20 on Digikey. :-)
    * 6MHz SPI clock
    * Used only store images, not to store firmware

* 3502EM-G1

    * AP3502E - 340kHz, 2A Synchronous DC-DC Buck Converter
    * datasheet

    
* Xtal
    
    * 32.768kHz

* HUB75 signals

    * LE: 2.13kHz

* Power

    * 4 AA batteries (so max 6.5V)
    * Screen starts flickering around 4.3V (max is 6.5V)
    * Max power consumption is around ~150mA when displaying a mostly white image
    * ~18mA when panel not connected

