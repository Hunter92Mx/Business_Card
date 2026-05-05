# Business_Card
Development of an electronic business card with NFC + battery charger + MCU

The driver for the Serial communication can be downloaded from the following link. https://www.silabs.com/software-and-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads

NFC antenna designer tool https://www.nxp.com/products/rfid-nfc/nfc-hf/nfc-readers/nfc-antenna-design-hub:NFC-ANTENNA-DESIGN-TOOL

NFC Application to format and Flash NFC chip https://play.google.com/store/apps/details?id=com.nxp.nfc.tagwriter

Log 05/05/2026 
- After testing this version, two errors were found in the board. The RX/TX of the CP2102N are inverted, and the DTR pin must be connected with the Reset pin of the MCU through a 100nF capacitor
