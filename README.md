# ch341 Linux SPI Driver (nRF24L01+ mod)

This driver provides /dev/spidev0.* and 2 GPIOs (4 and 5) using a ch341 USB bridge.
It was modified to allow GPIO4 to be used for NRF24L01+ CS Signal and GPIO5 to be used
as an interrupt input coming from nRF24L01 IRQ pin.

