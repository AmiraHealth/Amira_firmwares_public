# Amira_firmwares_public
Compiled firmwares for Amira devices

Latest firmware available in Releases section.

To flash firmware, you need to use either NRF Connect app or nrfutil command line tool.

## Flashing firmware using NRF Connect app
1. Download and install NRF Connect app from Google Play or App Store
2. Download firmware zip file from Releases section
3. Open NRF Connect app
4. Tap on DFU icon
5. Tap on Select File and select .zip file from step 2
6. Tap on Upload

## Flashing firmware using nrfjprog command line tool
1. Download and install nrfjprog command line tool from [here](https://www.nordicsemi.com/Software-and-tools/Development-Tools/nRF-Command-Line-Tools)
2. To flash the board `nrfjprog -f nrf52 --program HEXFILE_PATH --sectorerase`
3. To reset the board `nrfjprog -f nrf52 --reset`

Board should be programmed, **press the power button 5sec** to turn it on.

