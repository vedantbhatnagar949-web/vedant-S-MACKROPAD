🔥 VEDANT’S HACKPAD – RP2040 MACROPAD (Blueprint-Ready)

📌 Overview

Vedant’s Hackpad is a 4-button macropad powered by the Seeed Xiao RP2040 DIP board.
It’s designed as a custom fidget-tool + macro controller, inspired by the original Hackpad & Ducc’s Fidget Toy — but with Vedant’s own engineering, layout and housing.

This version is fully:

✔ PCB-ready

✔ KiCad project included

✔ Case design included

✔ Firmware plans included


Perfect for Hackclub Blueprint tickets, open-source hardware, DIY projects, and demos.


---

🎯 Features

🔘 4-Button Arrow Layout (Up / Down / Left / Right)

🔲 Based on Cherry MX footprint

⚡ Powered by Xiao RP2040 DIP

🟢 USB-C (native on Xiao)

📦 Custom 3D printed case (Fusion 360)

🔩 Single-side routed PCB

⚙ Open-source hardware



---

🧩 Block Diagram

+-----------------+
         |  Xiao RP2040   |
         |     (DIP)      |
         +-----------------+
             |    |    |    |
           BTN1 BTN2 BTN3 BTN4
           (UP) (DOWN)(LEFT)(RIGHT)


---

📐 PCB / Schematic

Your images go here (upload them to repo → copy raw URL → replace):

🔌 Schematic

![Schematic](SCHEMATIC_IMAGE_URL)

🟩 PCB Layout

![PCB](https://github.com/vedantbhatnagar949-web/vedant-S-MACKROPAD/blob/3dc53364e76417392b3968a57ba18b01744b9de8/pcb%20des.png)


---

🧱 Case Design (Fusion 360)

Your case files (.f3d or .step) are inside /case/.

Add preview image:

![Back Case](https://github.com/vedantbhatnagar949-web/vedant-S-MACKROPAD/blob/2fd6a118e8726c50f836976779d45e232714b1f4/backcase%20front%20.png)
![Front case](https://github.com/vedantbhatnagar949-web/vedant-S-MACKROPAD/blob/99a38b4c000b6e2918b5b748da4f7820e364b738/front%20case.png)


---

🛠 Components Used

Item	Qty	Notes

Seeed Xiao RP2040 DIP	1	Main microcontroller
MX Switches	4	Arrow layout
1N4148 Diodes (optional)	4	If using matrix
PCB	1	KiCad included
USB-C Cable	1	
3D Printed Case	1	Fusion 360



---

⚙ Firmware (Planned)

TBD (will add after PCB is finalized):

QMK-style button mapping

USB HID Keyboard emulation

Arrow keys:

UP → KEY_UP_ARROW

DOWN → KEY_DOWN_ARROW

LEFT → KEY_LEFT_ARROW

RIGHT → KEY_RIGHT_ARROW



Code will be written after final PCB test.


---

📂 Folder Structure

vedant-S-HACKPAD/
│
├── kicad/               # PCB & schematic
│   ├── hackpad.kicad_pro
│   ├── hackpad.kicad_pcb
│   └── schematics/
│
├── case/                # 3D model (Fusion 360 or STEP)
│
├── images/              # PCB & schematic screenshots
│
└── README.md


---

📦 How to Build

1. Download gerbers


2. Order PCB


3. Solder Xiao RP2040


4. Add MX switches


5. Flash firmware


6. Insert into printed case




---

🚀 Future Updates

RGB underglow

OLED / TFT support

Encoder wheel

Wireless BLE option

Macropad profiles inside firmware



---

👤 Author

Vedant Bhatnagar
14-year-old builder, designer & future hardware inventor ⚡
Follow for more open-source builds.


---

🪧 License

MIT — Free for everyone to modify and improve.****
