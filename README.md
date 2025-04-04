# ArtilleryX1-Switchwire

Repository to document my journey to convert my X1 to a Voron switchwire

### STL's are complete
I have sourced/updated, created everything needed to print out, with the exception of the stealthburner.
https://github.com/VoronDesign/Voron-Stealthburner

### You will also need the BTT cable holders for the canbus cable: 
"CW2 cable bridge" and "printed part for can cable" <br>
https://github.com/bigtreetech/EBB/tree/master/EBB%20SB2240_2209%20CAN/STL 
<br>
<br>
### I used these clips on the canbus cable and bowden tube:
https://www.printables.com/model/741489-bowden-tube-and-canbus-usb-cable-support-clips/files
<br>
<br>
<br>
### I also used these cable clips for the CanBus wiring 
https://www.printables.com/model/538726-voron-2020-aluminum-profile-cable-clip-bigger-size
<br>
<BR>
<br>
### The plan:
keep the following:
  - base and frame
  - heatbed and glass bed *WIll need a steel sprung plate for Eddy sensor
  - Y motion
  - Z steppers
  - mks gen L board and electronics
  - Optical endstop on Z and Y - if you use a EDDY usb, you can remove the Z optical endstop 

### To add:
- Voron Stealthburner
- Voron revo hotend
- micro switch for X on toolhead
  
### CanBus
  - BTT U2C USB bridge
  - BTT EBB sb2209 rp2040
  - canbus turorial here: https://github.com/bigtreetech/EBB
  
  - BTT Eddy Duo (Canbus or USB)
  - EDDY tutorial here https://github.com/bigtreetech/Eddy
    - I had a Eddy coil which uses I2C, so i wired that straight through to the Raspberry pi as the toolhead did not have I2C.
### MGN Rail
  - 2 x MGN 9 Rails for Z
    - 450mm
  - MGN 12 Rail for X
    - 350mm - cut down to 340mm
### Raspberry Pi 4
  - Standard RPI install with KIAUH install script to install mainsail, klipperscreen, crowsnest etc.
  - Here: https://github.com/dw-0/kiauh
        
### 5 Inch LCD - BTT TFT50
  - I remixed this one - https://www.printables.com/model/198864-btt-tft50-v20-casehousing-mount-revision-2/files
  - remixed STLs are in the electronics folder
  - A BTT TFT50 5 inch touch LCD.
  - 30cm Raspberry pi CSI cable 
  
### 5 volt Meanwell power supply for Raspberry Pi

### 2020 Vslot rail  
  This replaces the 2060 X gantry
  - 400mm cut to 380mm

### Screws etc
- M5 x 45 = 4
- M5 x 16 = lots
- M5 x 30 = 6
- M3 x 12 = lots
- M3 Drop in place t nuts
- M5 Drop inplace t nuts
- M3 heatset inserts - standard voron ones x 2 for the BTT50 screen mount

### Bearings and belt 
- F695-2rs = 16
 - or, i used these kits which are 6 tooth GT2 and 2 smooth - https://www.aliexpress.com/item/1005005767406346.html
- Gt2 Belt = 5 metres


![Switchwire](images/image1.png)
![Switchwire](images/image2.png)
![Switchwire](images/image3.png)
![Switchwire](images/image4.png)
![Switchwire](images/image5.png)
![Switchwire](images/image6.png)
 
  
     
