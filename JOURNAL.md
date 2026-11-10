---
title: ALU-HALF
author: dct00678
description: "Building a 74LS Half Adder: The Core Foundation of Modern Microcontrollers and ALUs"
created_at: 11-10-2026
---

# November 11 2026 / 🕗 8:20 - 8:40 PM
Started creating the schematic in KiCad cuz the last time that i was building schematics was in EasyEda and well it was REALLY bad!

Made the VCC AND GND connections of each Logic Gate, paired with a 0.1uf Capacitor. 
For the main breadboard power rails, i laid a 220uf / 10V capacitor to act as a bulk decoupling capacitor.

I paired the VCC and GND pins with a capacitor because my power supply is not stable it's being connected on my laptop so it's like a dc-dc, and it serves as a decoupling capacitor for low level voltage noises!

Note: Today i learned that we need to use pwr_flags for the vcc and gnd pin!!
<img width="866" height="559" alt="image" src="https://github.com/user-attachments/assets/24b7d313-a8dd-45d1-81e7-fdc124b77408" />


**Total time spent: 20 Minutes**

# November 11 2026 / 🕣 8:45 - 8:50 PM
Added the switches for the inputs of the Half Adder
I used SPDT Switches so when a another person builds this, they can manually change the state of each input. (I HATE USING PUSHBUTTONS!!)

SW = Switches

SW1 = Input A
SW2= Input B

<img width="813" height="760" alt="image" src="https://github.com/user-attachments/assets/ff493654-2b61-4f0f-97b9-997f7cb05339" />

**Total time spent: 10 Minutes**

# November 11 2026 / 🕣 8:55 - 9:25 pm

Built the 74LS Logic Gates, had a little mix up on the wires but resolved within 2 minutes
Used 20k Resistors for the base of the transistors then connected another 20k from the base to GND.
From what i have experienced, it's to avoid floating pins

<img width="650" height="581" alt="image" src="https://github.com/user-attachments/assets/c7193464-7c5f-431b-9700-57ab87db543a" />


**Total time spent: 30 Minutes**

# November 11 2026 / 🕤 9:25 PM - 9:45 PM
Ran the Electrical Rules Checker, and i got a message / error of the VCC and GND pin of the 74LS86 has been reversed, but it was quickly solved.


I also added the unused pins of each logic gates, and each of their inputs is put on GND to avoid their interference with the used inputs and outputs (common practice for me)

<img width="1120" height="770" alt="image" src="https://github.com/user-attachments/assets/412cf2fc-eee4-4d40-9193-df7f789404f2" />

**Total time spent: 20 Minutes**

# November 11 2026 / 🕤 9:50 - 
Assembly Time!

**THIS WILL ALSO BE A GUIDE FOR CREATING IT YOURSELF!!**

Get your breadboard and get the following:
1 74LS86N XOR GATE
1 74LS08N AND GATE
2 SPDT Switches
1 Electrolytic Capacitor | 220uf / 10V
2 Ceramic Capacitors | 0.1uf
Jumper Wires / Solid Core Wires

<img width="2032" height="914" alt="image" src="https://github.com/user-attachments/assets/d9953ebf-68f8-4403-839c-afb36bf512ee" />

**1. Put your electrolytic capacitor close to the entry point of your power supply**

<img width="912" height="2026" alt="image" src="https://github.com/user-attachments/assets/996ae073-2d34-4167-949d-ca538748732c" />

**2. Put your Logic Gates on the breadboard, XOR GATE FIRST, THEN THE AND GATE**

<img width="4096" height="3072" alt="image" src="https://github.com/user-attachments/assets/29c9b1e9-148a-4921-baff-d6bf78e81d6f" />


**3. Connect your ceramic capacitors, put it near and closest to the vcc and gnd pin like shown in the picture** 

<img width="4096" height="3072" alt="image" src="https://github.com/user-attachments/assets/4ece94c7-e4f2-4913-835b-a4faa4bdf938" />

**4. Connect the VCC and GND pins to each side of the ceramic capacitor, and wire it to the appropriate power supply
<img width="1080" height="1920" alt="image" src="https://github.com/user-attachments/assets/c77331fe-7a42-46a4-8cd5-cedb6f793bc9" />

**5. Connect the switches on the breadboard** 
<img width="912" height="2026" alt="image" src="https://github.com/user-attachments/assets/331a90f7-ab3b-40fb-b6d2-4fbcb253526c" />

**6. Connect the switches to their appropriate logic gate inputs
It should be this: 
**Total time spent: 30 Minutes**

