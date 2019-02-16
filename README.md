# ADV7513

This is a small development board for the [Analog Devices ADV7513 HDMI Transmitter][ADV7513]. It's designed to be hand-soldered.
I also wrote some code for initialisation (via I2C) in verilog. This can be found as part of my [Dreamcast HDMI][DreamcastHDMI] project. 

[![board][oshpark]][oshparkorder]

[ADV7513]: http://www.analog.com/en/products/audio-video/analoghdmidvi-interfaces/analog-hdmidvi-display-interfaces/adv7513.html
[DreamcastHDMI]: https://github.com/chriz2600/DreamcastHDMI/tree/master/FPGA-CycloneIV-ADV7513

[oshparkorder]: https://oshpark.com/shared_projects/b1enkRm7
[oshpark]: https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png

### BOM

- `U1`: [ADV7513](http://www.analog.com/en/products/audio-video/analoghdmidvi-interfaces/analog-hdmidvi-display-interfaces/adv7513.html)

    This seems to be a little harder to get from an official distributor, if you are not an HDMI licensee. 
    
    You can get it from [Aliexpress](https://www.aliexpress.com/wholesale?SearchText=ADV7513)

- `U2`: [NCP1117DT33G](https://www.digikey.com/products/en?keywords=NCP1117DT33G)
- `U3`: [NCP1117DT18G](https://www.digikey.com/products/en?keywords=NCP1117DT18G)
- `J1`: [HDMI Connector](https://www.digikey.com/product-detail/en/amphenol-icc-fci/10029449-111RLF/609-4614-1-ND/2785376)
- `U4, U5, U6`: [TVS_DIODE](https://www.digikey.com/product-detail/en/diodes-incorporated/D5V0F4U10MR-13/D5V0F4U10MR-13DICT-ND/4473969)
- `C1, C7, C9, C11, C17, C18`: 10u (0805)
- `C2, C3, C4, C5, C6, C8, C10, C12, C13, C14, C15, C16`: 100n (0805)
- `R1, R2, R5, R6, R7, R8`: 2K (0805)
- `R3`: 887R (0805)
- `R4`: 10K (0805)
- `L1, L2, L3, L4`: 10u (1210)
