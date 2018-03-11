# EasyInjection
EasyInjection is a module to drive fuel injectors. It has 4 channels.

Some aftermarket EFIs has only low power signal output to activate injectors.

So, an external driver is needed. The EasyInjection can be this driver.

EasyInjection works perfectly with MegaSquit EFI.

# Technical Information
EasyInjection is based on VND5N07.

VND5N07 is a power MOSFET fully autoprotected. 

It's a great option to drive fuel injectors with a minimum set of components.

EasyInjection can be used with high-z injectors, but some low-z injectors can be used (specially if use a in serie resistor), because VND5N07 supplies up to 5A.

The project was developed using Kicad EDA.

# Usage
EasyInjection works switching the ground (GND).

Pins 3 and 8 must be connected to a good engine ground.

### Input signals (from EFI):

- Channel 1: Pin 2
- Channel 2: Pin 1
- Channel 3: Pin 5
- Channel 4: Pin 4

### Output (to injector):

- Channel 1: Pin 6
- Channel 2: Pin 7
- Channel 3: Pin 9
- Channel 4: Pin 10


More than one injector can be drive by channel, with 5A current limit for each channel.

More than one module can be used, to drive more injectors.



# License
This project is under dual-license.

First license is for commercial use of this project. To build a product, based on this project, and sell it.

Second license is for non-commercial use of this project. To build a sample, to personal use or education use.

# Donate
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=B875H7TZRFDBL&lc=BR&item_name=DDO%20Engineering&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

