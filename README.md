# ALU-HALF

<img width="526" height="522" alt="image" src="https://github.com/user-attachments/assets/b6616b9c-4691-4656-b248-8b572d407902" />

I built this circuit or Half Adder to help new hobbyists & beginner enthusiasts understand how the basics of Digital Electronics work!!
This circuit helped me understand the basics of Binary Addition, so why not build it and share it to others? :)

A Half Adder uses 1 XOR Gate and 1 AND Gate.
In my version, we will use the 74LS Series and NPN Transistors for the outputs
Since 74LS Logic Gates cannot provide enough power for sourcing, we will use NPN transistors to make it functional for our LEDs through sinking!

And it takes 2 inputs, 1st input is A, 2nd input is B.
The XOR Gate acts like the SUM of the two inputs, so if only one input is high, then the XOR Gate is through.
In binary addition, 1 + 0 = 1.

And if both inputs are HIGH, the output the XOR Gate is LOW.
Then the AND Gate enters here, or the extra / carry.
Since AND Gate is HIGH if only both inputs are HIGH, then the inputs are true!
In binary addition, 1 + 1 = 0, and we have to carry the C_OUT somewhere, and the AND Gate is appropriate here!

This circuit exists because Half Adders are one of the fundamentals needed in creating todays machine and MCUS. (Microcontroller Unit)



DEMO VIDEO:

https://www.youtube.com/watch?v=myyzes973is
