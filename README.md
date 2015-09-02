# CircuitBoardTutorial
This tutorial describes how to create your very own printed circuit board (PCB) using the tools in Art & Technology Studies ioLab at the [School of the Art Institute of Chicago](www.saic.edu).  Here's what we will cover in this tut:

1. Using [Fritzing](www.fritzing.org) to design the PCB for your project.
2. Exporting and preparing that design for the circuit board mill.
3. Setting up the mill and running a mill job.
4. Finishing your PCB and preparing to put it into use.

For this tutorial, let's assume that you already have [downloaded](fritzing.org/download) Fritzing, you have designed your PCB, you have some electronics experience and that you're proficient at breadboarding a circuit, soldering, and checking continuity with a multimeter.  I will be touching briefly on the example design, but there are many more in-depth tutorials over at http://fritzing.org/learning/.

Ok, let's get started!!

## 1. Using Fritzing to design the PCB.
If you're ready to design and fabricate a PCB, that usually means that you have already worked out your circuit on a breadboard.  You may even have soldered up one or two of said circuit on a protoboard. A dedicated PCB can save you space and keep you from having to solder a million jumpers all over your protoboard.  For this tutorial, we're going to use a modified version of the [555 Timer LED Flasher](http://fritzing.org/projects/555-timer-led-flasher) from Fritzing's projects page.  The astable 555 circuit is a oldy and a goody and it will show some of the features of that can make a PCB more desireable than a protoboard.  [Here](https://github.com/noahcoleman/CircuitBoardTutorial/blob/master/555%20Timer%20IC.fzz) is the Fritzing file we'll be using.

So, we're going to open that up in Frizting, which should look a little something like this:
IMAGE OF FRITZING-breadboard view
We are so done with breadboarding, though.  Let's move on to the PCB page.  To get there you want to click on the button that says "PCB" up at the top of the page.  Alternatively, you can press ⌘4 to get there.

IMAGE OF FRITZING-- pcb view
Ok, so now we have the pcb view up, and you can see that I have all my components placed and the traces properly routed.  Just as a side note, the big empty space on the right is going to be for our potentiometer.  Once I've got everything finalized, I want to do a quick design rules check to make sure I haven't crossed any traces--this becomes more important with more complex boards.







