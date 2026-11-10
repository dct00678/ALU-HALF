---
title: ALU-HALF
author: dct00678
description: Building a 74LS Half Adder: The Core Foundation of Modern Microcontrollers and ALUs
created_at: 11-10-2026
---

# November 11 2026 / 🕗 8:20 - 8:40 PM
Started creating the schematic in KiCad

Made the VCC AND GND connections of each Logic Gate, paired with a 0.1uf Capacitor. 
For the main breadboard power rails, i laid a 220uf / 10V capacitor to act as a bulk decoupling capacitor.

I paired the VCC and GND pins with a capacitor because my power supply is not stable, and it serves as a decoupling capacitor for low level voltage noises!

<img width="866" height="559" alt="image" src="https://github.com/user-attachments/assets/24b7d313-a8dd-45d1-81e7-fdc124b77408" />


**Total time spent: 20 Minutes**

# November 11 2026 / 🕣 8:45 - 8:50 PM
Added the switches for the inputs of the Half Adder
I used SPDT Switches so when a another person builds this, they can manually change the state of each input.

SW = Switches

SW1 = Input A
SW2= Input B

<img width="813" height="760" alt="image" src="https://github.com/user-attachments/assets/ff493654-2b61-4f0f-97b9-997f7cb05339" />

**Total time spent: 10 Minutes**

# November 11 2026 / 🕣 8:55 - 9:25 pm

Built the 74LS Logic Gates, had a little mix up on the wires but resolved within 2 minutes
Used 20k Resistors for the base of the transistors then connected another 20k from the base to GND.
This avoids floating of pins..

<img width="650" height="581" alt="image" src="https://github.com/user-attachments/assets/c7193464-7c5f-431b-9700-57ab87db543a" />


**Total time spent: 30 Minutes**

# November 11 2026 / 🕤 9:25 PM - 9:45 PM
Ran the Electrical Rules Checker, and stumbled upon the VCC and GND pin of the 74LS86 has been reversed, but it was quickly solved

Also added the unused pins of each logic gates, and each of their inputs is put on GND to avoid their interference with the used inputs and outputs

<img width="1120" height="770" alt="image" src="https://github.com/user-attachments/assets/412cf2fc-eee4-4d40-9193-df7f789404f2" />

**Total time spent: 20 Minutes**

# November 11 2026 / 🕤 9:50 - 
Assembly Time!
**Total time spent: 30 Minutes**

