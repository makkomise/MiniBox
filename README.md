# MiniBox

![picture of the controller](https://i.imgur.com/Pw6ptVj.png)

(First proto, files have been updated to v2, which loses the middle button as it is not really needed, and pcb changed to north-facing LEDs.


## HitBox-style controller, made as small as feasible. Powered by [GP2040-CE!](https://gp2040-ce.info/) 

- PCB-Folder includes all the necessary things for ordering a PCB. 
- Alternatively, you can make this one without PCB, .stl-files needed are located in the STL -> NOPCB folder. NOTE: This version doesn't get to enjoy all the fancy RGB, and this is yet untested nor built so do at your own risk. 

- Firmware-Folder has the backup of GP2040-CE settings, with the pinout for the PCB. If you don't use the PCB, you can map buttons yourself. Download firmware from here: [https://github.com/OpenStickCommunity/GP2040-CE/releases/download/v0.7.10/GP2040-CE_0.7.10_WaveshareZero.uf2/](https://github.com/OpenStickCommunity/GP2040-CE/releases/download/v0.7.10/GP2040-CE_0.7.10_WaveshareZero.uf2)

- STL-Folder has the 3d-files needed for printing, just make sure you get the right ones since the others are meant to use alongside with pcb while the others aren't. NOTE: I have not printed this myself, i ordered prints from JLC3DP. IDK how your printers handle this, nor if you need to add supports or anything. That's your own responsibility, not mine. 

## NOTE:
- If you build this without a PCB, beware of the really tight tolerances. Solder wires so that they don't protrude over the pins or you might not be able to close the case.

## BILL OF MATERIALS:

- Low-profile switches, 10pcs: PCB is made for Kailh Chocolate V2-switches, and i highly recommend [these kailh deep sea silent's](https://www.aliexpress.com/item/1005007612020460.html). If you're building one without a pcb, any low-profile switch will do. Probably. Because there is twenty standards with different measurements with these, some switches may actually be too tall for these. Just get those Kailh ones, they're good. Or any of [these](https://diykey.net/products/all-pom-low-profile-keyboard-switch-tactile-switch).
- Buttons/Keycaps: I used [These Duelpad ones](https://www.aliexpress.com/item/1005006860432524.html), but technically any MX-stemmed 20.2mm diameter round button will work.
- Waveshare RP2040-Zero. Both versions of the case are built around this specific model, can't guarantee compatibility of any other dev boards, because of the dimension restrictions of the case. 
- 2pcs of 12*12*7.3MM tactile buttons with A24 button caps. NOTE: because of VERY tight tolerances, some buttons are just a bit too tall out of the box. You can shave 1mm off from the button legs, they still work fine and fit perfectly.
- 5pcs of regular ol' computer fan screws, we all have box of these laying around, right?!?
- Soldering iron and wire(duh)
  
### FOR PCB:
- 5pcs of 100nF 1206-capacitors.
- 10pcs of SK6812MINI-E rgb LEDs.

