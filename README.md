![Image_1](https://github.com/user-attachments/assets/1f53934b-901b-43cd-b2ab-cb73106fb4a7)
# Introduction
Part of the inspiration of this project came from frequently having guests over. One of the first things guests will ask is the WiFi password. At some point, this inspired me to create a quick way to access WiFi; this is when I learned about NFC tags. This project is made up of two parts, a 3D-printed NFC holder and an NFC tag. The first part, the 3D-printed NFC holder is shown in the next section.
# 3D-Printed NFC Holder
![Image_2](https://github.com/user-attachments/assets/b41147e2-9f19-4dc0-9982-c1df23b03557)
I wanted a simple design for this NFC Holder. I designed it on OnShape and then proceeded to print it using my Original Prusa Mini+ and using PrusaSlicer.
# Specifications & Material(s)
## 3D Printer
 Original Prusa Mini+
## Material(s)
* [INLAND Marble PLA Filament ($29.99)](https://www.amazon.com/Inland-1-75mm-Marble-Printer-Filament/dp/B08M4733VV/ref=sr_1_3?crid=RY0788Z9D3XL&dib=eyJ2IjoiMSJ9.GvDUjGeacdaThMoKB2T31ewH9i3JmlLfhoDydChHBm-pD7cXPBEVjrKUewiIA1ZLE0_09V1n0PRn75b7hFqiDw4M0-lnl6NiRKwU4Bay_UQglrp8aVfnSITNRxxnTlk00zi7jk9JMRR5mzHilVguVNlu22jSBhxaIA2Mgu28qpM98QySMqZ0onKGj8rI2Ae99hyhSl7nTwlWuBccngRzfk5tlxoLLDb3Ck8adz-NTaQ.5vcyT03Wl1FkUx1DENvwhSOMvdqbl_TQCjXICAq7kSI&dib_tag=se&keywords=pla+filament+inland+marble&qid=1735843633&sprefix=pla+filament+inland+marble%2Caps%2C87&sr=8-3
)
# Software
 PrusaSlicer
 ![Image_3](https://github.com/user-attachments/assets/74f0e6df-54ff-4fed-aae8-e25df3ee9b7c)
 ## Settings
  Layer Height: .2mm \
  Infill: 50% \
  Supports: None \
  Estimated Printing Time: 25 minutes
# NFC Tag
![Image_4](https://github.com/user-attachments/assets/c1b4d1c5-4d13-4bfa-ba43-939e600c45c2)
The NFC tag is pretty simple to program using an Android phone and I’m sure you can use an iPhone as well.
# Initialization & Material(s)
Below you will find how I programmed the NFC tag and where it was purchased from.
## Initialization
I downloaded an app on the Play Store called NFC Tools; it is by wakdev. This app is incredibly useful and easy to use. When you first boot it up, this is what you’ll likely see:
![Image_5](https://github.com/user-attachments/assets/709e5967-18a4-4f82-8129-4af43c3fc6cd)
From here, tap your NFC tag; the following menu will appear.
![Image_6](https://github.com/user-attachments/assets/3fd644d4-7bb9-46e7-9eba-37c86f9be996)
Go to Write -> Add a record -> Wi-Fi network. Enter the details of your WiFi network. Most home networks will be WPA2-Personal, with encryption “None” Then enter your WiFi network’s name and password. Make sure to abide by all letter cases in your WiFi network.
![Image_7](https://github.com/user-attachments/assets/ba18c4d6-4081-48e1-9223-4f5cc5dcb9ef)
The last thing left is the most critical: Make sure to press the “Write” button and then step away from your NFC tag and approach it again. Once it is completed, you should see this:
![Image_8](https://github.com/user-attachments/assets/31dc1378-8515-458f-8f18-602377ca62ee)
Now, the next time you approach the NFC tag, you will be prompted on whether on not you wish to join the WiFi network written on it.
## Material(s)
* [NFC Stickers ($7.96)](https://www.amazon.com/Stickers-NTAG215-Programmable-Compatible-Android/dp/B091FCDPDR/ref=sxin_16_pa_sp_search_thematic_sspa?content-id=amzn1.sym.27b41115-b206-47c3-8621-713097e8442c%3Aamzn1.sym.27b41115-b206-47c3-8621-713097e8442c&crid=2CUK9W8I3L1WZ&cv_ct_cx=nfc%2Btags%2Bk%2Blakey&keywords=nfc%2Btags%2Bk%2Blakey&pd_rd_i=B091FCFJT9&pd_rd_r=1cfacf3c-cea7-49fc-9283-38dc8e35ebf4&pd_rd_w=3jGhz&pd_rd_wg=fOWr0&pf_rd_p=27b41115-b206-47c3-8621-713097e8442c&pf_rd_r=T2JE71K6VYQHEHNZ605T&qid=1735842929&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=nfc%2Btags%2Bk%2Blakey%2Caps%2C74&sr=1-1-6024b2a3-78e4-4fed-8fed-e1613be3bcce-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9zZWFyY2hfdGhlbWF0aWM&th=1
)
# Tips
You may have an issue ensuring that your phone can read the NFC tag. I recommend, for at least Android and the process is likely similar for iOS, going to Settings -> Connected Devices -> Connection Preferences -> NFC (and turn this on).

Your guests may also have issues connecting to the network if their phone has a thick case or if they are not tapping the correct part of the phone to the NFC tag. Removing the case and moving the phone around until it reads the tag helps with this, but this is easier for some than others.

I used some velcro to attach the WiFi NFC Tag to the wall near the entrance of my house so guests have easy access, but I also have a copy lying around on a desk near the kitchen. You can do whatever floats your boat.

