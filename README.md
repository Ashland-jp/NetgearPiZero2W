# Netgear Nighthawk WiFi Extender gutted 
# for Raspberry Pi Zero 2W 
## missing instructions for pihole***

## Introduction

In this project, I transformed a Netgear Nighthawk WiFi extender into an Ad blocking PiHole. The goal was to repurpose existing hardware and create a custom solution for network analysis and WiFi management.

## Materials and Tools

- **Netgear Nighthawk WiFi Extender**
- **[Raspberry Pi Zero2W](https://www.amazon.com/Raspberry-Zero-Bluetooth-RPi-2W/dp/B09LH5SBPS)**
- **PC with [Raspberry Pi Imaging](https://www.raspberrypi.com/software/) tool**
- **[Official PiHole ISO file](https://pi-hole.net)**
- **Old 1A iPhone Charger**
- **[Micro USB to USB OTG Adapter](https://www.amazon.com/Ksmile%C2%AE-Female-Adapter-SamSung-tablets/dp/B01C6032G0/ref=sr_1_4?crid=13J28UFBM5ROC&dib=eyJ2IjoiMSJ9._OJCH-bOkx9S1uHBtnyZZ7Bwe4m31RF6mjLWPCA5lfJNbzUZjqWGziHMo1tVmQGTbl8UB1_ZRRs9EMNnkMg9nB51F4hWFKY-FlLBPiP4r_hS_qHby3wne-IW8S9f3ep6gcLITjpbyTxAqBEeu6aN-8xwk7_rLhF7UfvpbCgwhW3aSiGWbrsSBoLnvwmlgBhDZXn_A8Y7TfM426K58QSsAxkT4cyoliIWwMVGaewshJU3laBqNyNS0y4yOjVdcBWyMt-6CyneJJLrkhpkB0nffyXBZ_HQdO-xfvX1TNvg8aY.pBQTkXPT6KqJpJjKuElDwaslkN243sDIVyVEji96EQ0&dib_tag=se&keywords=micro+usb+to+usb+adapter&qid=1760474324&s=electronics&sprefix=micro+usb+to+usb+adapter%2Celectronics%2C593&sr=1-4)**
- **Soldering Kit**
- **Hot Glue Gun**
- **Saw**

## Steps

### 1. Disassembly of the WiFi Extender

- Carefully disassemble the Netgear Nighthawk WiFi extender. There are 4 philips screws to remove.
  Then there are two tabs on top and bottom of device that you press in to open the face.
- Remove all internal components, keeping only the prings for the outlet attached. If you're careful enough,
  you can save the 4 pins on shell of the Ethernet jack to make the lights function. Very easily reassembly as well.

### 2. Preparation of the Raspberry Pi Zero2W

- I followed a walkthrough to install PiHole properly but I will do a brief overview and link the video I used.
  I downloaded the Raspberry Pi Imager from the official website listed above as well as the ISO image from PiHole.net
  Check your file hashes with the ones they give. Dont end up with a tool that has a straggler crypto wallet drainer lol.
  Choose your SD card from the list, load the ISO and were almost ready! 

### 3. Modifying the iPhone Charger

- I cut open the 1 amp iPhone charger leaving 90% intact only removing one side. PLEASE WEAR RUBBER GLOVES! The capacitor may still hold charge and will bum you out.
- I then soldered the + and -  leads to the outlet prongs. I guessed which were which it doesnt matter where we're going.
- Secure the soldered connections with hot glue to ensure durability and safety.
- This will be used to power the Raspberry Pi "safely".
  
### 4. Integration into the Extender Case

- The Nighthawk has these two small plastic tabs. I was able to sit the RPi ontop of the charger and slot the RPi into these two tabs.
  It holds it nicely. Place the Raspberry Pi Zero2W into the now-empty WiFi extender case. 

  **DISCLAIMER:** I cut the side of the case to adapt a USB-A port to the side of the device so I could attach peripherals if neccesary.
                  If you run this headless you dont need the adapter at all and the device will look factory.

- Cut a slot into the side of the case for the micro USB to USB A adapter. This modification looks fairly decent and provides a secure connection for external peripherals.

### 5. Assembly

- Reassemble the WiFi extender case with the Raspberry Pi Zero2W and power setup inside. The case should now be a functional enclosure for the new device.
- Ensure all components are firmly secured and that there’s no risk of short circuits.

### 6. Testing

- 
- Power up the modified WiFi extender and verify that the Raspberry Pi Zero2W boots correctly and operates as expected.
- NEXT SECTION UNDER CONSTRUCTION

## Final Touches

The end result is a compact, portable device that leverages the existing WiFi extender case to house and protect the Raspberry Pi Zero2W. The integration of the old iPhone charger and the USB adapter maintains a clean and professional appearance while enhancing the functionality of the original hardware.
