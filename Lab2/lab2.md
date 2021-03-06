# Prelab 2 Reference Information 
----------

Disclaimer: 
>Any views or opinions presented in this website are solely those of the author and do not necessarily represent those of the University of Nevada, Las Vegas and its employees, the Department of Electrical and Computer Engineering, Dr. S. Harris, Brandon Blackstone, or the various institutions listed here. I gain nothing from your use of this site. So now I can say that your mileage may vary, I hold no responsibility or guarantee anything on this site or this site itself helping you in your courses or in life. Use this at your own risk.
-----------

For the entirety of the prelab refer (THAT DOESN'T MEAN READ THE ENTIRE THING) to the [Atmel Documentation Homepage](http://www.atmel.com/webdoc/index.html), [Atmega Datasheet](http://www.atmel.com/Images/Atmel-42735-8-bit-AVR-Microcontroller-ATmega328-328P_Datasheet.pdf) and the [AVR ISA Manual](http://www.atmel.com/images/Atmel-0856-AVR-Instruction-Set-Manual.pdf) and chapter 2 of 	Programming and interfacing Atmel AVR microcontrollers by Thomas Grace which is freely available through UNLV's Lied Library [Direct Link which might not work](http://webpac.library.unlv.edu/search~S1/?searchtype=.&searcharg=b5268249). Additionally for a better details that were discussed in CpE 300 please refer to Digital Design and Computer Architecture, 1st Edition, available through the UNLV Library. Finally you may find it useful to refer to [The AVR Beginners Site](http://www.avrbeginners.net/). The sections below are what we are covering theoretically, so you can look them over and match to the above documents appropriately.

As such you have TWO options to learn from if provided. This only applies to Part 2, Part 4 and Part 5.  

-----------------------
Complaints: 
WHY ARE WE READING SO MUCH??? This is all review for you guys, none of this is new material theoretically. As such this isn't a challenge. You've either covered it in class, in lab previously or in CpE 300/EE320/CS218/CS135. This is just a formalization of concepts you know applied to a particular ISA. 

### Part 1, Software Developer Point of View (Links): 
Read through the following pages: [AVR Memory Map](http://www.avr-tutorials.com/general/avr-memory-map), [AVR Program Counter](http://www.avr-tutorials.com/general/avr-program-counter), [AVR](http://www.avr-tutorials.com/general/avr-microcontroller-stack-operation-and-stack-pointer)
Additionally, in the AVRbeginners site check the section on the Stack
-------------

### Part 2, AVR Architecture Internals (Either Datasheet or Links): 
A)Atmega328p Section 11 (page 25 onwards) 
B) Links below
Avrbeginngers section on the ALU
[AVR SPECIAL FEATURE, HARDWARE MULTIPLIER!](http://www.atmel.com/images/Atmel-1631-Using-the-AVR-Hardware-Multiplier_ApplicationNote_AVR201.pdf)

------------------------

### Part 3, AVR Assembly [LINKS]: 
Refer to the ISA Manual Listed Above and [Atmel AVR Documentation on the AVR Assembler](http://www.atmel.com/webdoc/avrassembler/index.html), [AVR Assembler Details](https://www.codeproject.com/Articles/712610/AVR-Assembler) as well as AVR Beginners on AVR Assembler

---------------

### Part 4, What is a Toolchain: 
Either A) [Atmel Application Note](http://www.atmel.com/Images/avr8-gnu-toolchain-3.5.4.1709-readme.pdf)
or
B) [AVR GCC OVERVIEW](http://www.nongnu.org/avr-libc/user-manual/overview.html) & [Assembler Details + Example](http://www.nongnu.org/avr-libc/user-manual/assembler.html)

--------------

### Part 5, AVR Memory [Either Datasheet or Links]: 
A) Atmega 328p Datasheet Section 12 (page 34)
B)
Read through the following sections: [AVR Architecture Information](http://www.avrbeginners.net/). Under the AVR Architecture Heading, look at the sections SRAM, Flash and EEPROM Memory.
[Types of AVR Memory](http://jeelabs.org/2011/12/05/types-of-memory-for-an-atmega/)

----------------

### Part 6, Programming the AVR [Entire Contents]: 
From page 360 to 365 in the Atmega328p Datasheet 
[General AVR Programming Overview](http://www.ladyada.net/learn/avr/programming.html)
[Atmel Application Note](http://www.atmel.com/Images/Atmel-0943-In-System-Programming_ApplicationNote_AVR910.pdf)
[General Software Side overview of Compilation](http://spimsimulator.sourceforge.net/HP_AppA.pdf)
[DIY ISP](https://learn.adafruit.com/usbtinyisp/overview)

----------------------

### Part 7, Breadboarding the Atmega [Entire Contents]: 
##### Required: 
Download/Bookmark this image for reference: [Atmega328p Pinout](https://www.arduino.cc/en/Hacking/PinMapping168)

Read Lecture 1 and 2 from the following site [Sparkfun Beginning Electronics ](https://www.sparkfun.com/tutorials/category/1)

If you've forgotten details on Breadboard usage please read here: [Sparkfun Breadboard Tutorial](https://learn.sparkfun.com/tutorials/how-to-use-a-breadboard)

Alternative links on Atmega328p Breadboarding, 
##### these are for reference/optional: 
[Arduino Breadboard](https://www.arduino.cc/en/Main/Standalone), [Jameco Tutorial](https://www.jameco.com/jameco/workshop/jamecobuilds/arduinocircuit.html), [ULTRA MINIMAL CIRCUIT FOR BAREBONES FUNCTIONALITY](https://www.avrprogrammers.com/atmega/atmegaxx8)


----------------

### Part 8, Debugging the AVR [Entire Contents]: 
[Debugging Best Practices](http://www.best-microcontroller-projects.com/article-debugging.html)

---------------

### Part 9, Simulating the AVR [Entire Contents]: 
[For Atmel Studio](http://www.atmel.com/webdoc/simulator/simulator.wb_Simulator_Use.html)
[SIMAVR for Linuxl](http://www.instructables.com/id/Debugging-AVR-code-in-Linux-with-simavr/?ALLSTEPS)

---------------------

### Part 10, Design and Development Cycle:
You should already have an idea about this from the very first lab lecture, but this is the process fully formalized. 
[The Embedded Systems Design and Development Process](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/C7_DesignDevelopment.htm)
--------------------------

The following is not necessary for this lab but Dr. Harris would like you to understand how to Solder. If there are any questions we can go over it lab next week when we actually work with boards. 

For now refer to the following links: [Sparkfun Detailed Soldering Tutorial](https://learn.sparkfun.com/tutorials/how-to-solder---through-hole-soldering) and [Adafruit Soldering Tutorial Videos](https://learn.adafruit.com/collins-lab-soldering/video)

