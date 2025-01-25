Note: Be sure to read this before using the PC, as it is very buggy, and has many issues. If you find any new issues, please let me know and I'll fix it as soon as possible!



 - What is this?

This is a project to build my own custom computer from scratch. It runs in Logisim Evolution, made out of basic circuits, and runs via a custom assembly language (BARELY). Although I built this computer myself, I did get help from many people. I will list them at the end of this.

- I downloaded the file, how do I open it?

In order to use this, you need Logisim Evolution. If you don't, you can find it on Github. Once you open the file in Logisim, you'll be in a circuit called "Gfgg PC 8". Just zoom out, and you should see it.

- How does this computer work (and why doesn't it half the time)

This computer runs on a custom assembly language I created called Gfgg Assembly, which is extremely basic. If you want to learn more on it, use the .pdf file I added. Use the binary code next to each instruction, convert
it into hexadecimal, then put it in the computer, it will then run once you start the clock or manually use the "MIN" input on the Program Counter to increment the ROM address (I know it's a hassle).

Note 2: For loading values into Reg A & B, the X's on the PDF file represent a 4-Bit binary number. There is no conversions to decimal, and stuff such as carrys and flags don't work currently. They will be added in a later revision.

- I don't know what to do!

I don't really have a guide, but I'll try my best here:

1. Using the PDF, create a basic program (Must be maximum 8 Bytes).
2. Using the PDF, convert the pnemonics into binary code.
3. Convert it to hexadecimal (I will try to write a python script for this at one point.)
4. Go to the ROM, right-click it and choose "Edit Contents". You can then replace what's currently there with your program.
5. On the top right of Logisim, click simulate, then click the third button (or the one in the middle). This should start the clock and get your program going.
6. If your program has a HALT instruction (Recommended), it will stop the Program Counter from incrementing, stopping the computer.

- Do you plan on fixing / improving this?

Yes, although this currently has many issues, I do want to make this more powerful. I know there's a lot missing, but I will take my time and learn more about this. Here are some plans on what I want to at least get working currently.

- Increase PC to 4-Bit (16 Byte programs)
- Get RAM working (I'll try 4 Bytes of RAM first, but I may have to decrease it if issues occur)
- And more in the future..

I know it's complicated, but I will take time learning more to make this more user-friendly. At this stage, I'm just trying to get feedback and reviews.

People who I watched to understand this better:

- Sebastian Lague
- Core Dumped
- Ben Eater
