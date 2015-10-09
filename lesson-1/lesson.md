# Lesson 1 - Getting started with Raspberry Pi

The Raspberry Pi is a tiny computer smaller than a pack of cards, which can transform the way we perceive and approach computation. In this lesson we will introduce the basic components of the Raspberry Pi and how they relate to a traditional computer.

We will discuss the general nature of computation and how the same computer can be programmed to simultaneously do many different things, from word processing to music synthesis. Finally, we will introduce the most basic principle of programming: a program as a sequence of instructions.

## Learning objectives

- Know the basic architectures of a computing device.
- Understand the difference between hardware and software.
- Be able to set up a Raspberry Pi, turn it on, load the graphical user interface, and navigate the desktop for the first time.

## Learning outcomes

**All students are able to:**

- Plug the components of a Raspberry Pi together.
- Understand that computers are general-purpose devices, and that not every computer obviously resembles one.
- Identify the basic architecture of a computer: processor, storage, and input/output.

**Most students are able to:**

- Set up a Raspberry Pi for the first time, log in, and load the graphical user interface.
- Identify different types of computers and explain what makes them a computer.
- Understand basic architecture of a computer: processor, storage, and input/output.

**Some students are able to:**

- Set up a Raspberry Pi, log in, and load the graphical user interface without assistance.
- Explain, with examples, the similarities and differences of a Raspberry Pi compared with a personal computer.

## Lesson summary

- An introduction to the basic physical parts of a Raspberry Pi
- An introduction to two types of computer interface:
	- command line
	- graphical

## Starter

Distribute the [computing device cards](files/Computing-Device-Card-Sort.zip) to pairs of students. Ask them to match the device to the description. Then ask students to create two piles: one for devices that they think are a type of computer, and one for devices they do not think are types of computers.

After a few minutes discuss the outcomes of this task with the class. Note that all the cards are types of computing devices! Draw on students answers to discuss what makes a computer.

## Main development

1. Watch the official ['What is a Raspberry Pi?'](https://www.raspberrypi.org/help/what-is-a-raspberry-pi/) animation.
	
	The animation is available on [Vimeo](https://vimeo.com/90103691) and [YouTube](https://www.youtube.com/watch?v=uXUjwk2-qx4)

1. Start with all the parts of the Raspberry Pi on a table:

	- keyboard
	- mouse
	- SD memory card
	- power supply
	- monitor
	- monitor cable
	- Raspberry Pi

	Ask the class to name and describe each component as you connect it to the Raspberry Pi in front of them.

	Explain that these components are **hardware**. Hardware refers to the physical elements of the computer that you can see and touch. This includes what is sometimes hidden inside the case.

	Finally, plug in the power and watch it boot up. An alternative demonstration would be to leave out the memory card and attempt to boot the Pi, which will fail. You can then describe the memory card as something that contains instructions to tell the Raspberry Pi how to start.

1. Demonstrate that the Raspberry Pi is a **standard** computer by opening up some applications and closing them again. If you are able to connect the Raspberry Pi via a network connection, then open up a web browser and surf to several different sites.

	Explain that this is software. Software is the term given to programs that run on the computer system and make the hardware work. Software has many uses, such as making a calculation or organising files. There are two main types of software: system software which runs and manages your computer, and application software which performs a specific task or function.

1. Distribute equipment to students and ask them to set up their own Raspberry Pis. Distribute the power supplies last, checking that students have connected their cables and SD cards correctly before they are powered up.

1. Ask students to log in to their Pis for the first time using the following login information:

	```
	Login: pi
	password: raspberry
	```

	Note that students will not see any text when typing the password but assure them it is working. Why do they think this might be the case? *Hint: what might happen if someone was looking over their shoulder?*

	If you are uisng the latest up to date software then you should boot straight to the desktop environment or **Graphical User Interface** If you are using older software then they will need to load the GUI by typing 'startx'. Once logged in, explain to the students that they can give instructions to the Raspberry Pi using the **command line interface** instead of the GUI.

1. Ask them to identify any parts that they recognise such as the desktop, task bar, menu system, mouse pointer, icons, etc. Ask students to load a `Terminal` window by clicking on **Menu**, **Accessories** and **Terminal**. This is what the **command line interface** looks like. Ask students to try different commands like `ls` to list files and directories and 'cd' to change between directories.

1. As an extension task, ask students to compare a Raspberry Pi to a desktop computer. What are the similarities? What are the differences? In what situations could you use a Raspberry Pi instead of a desktop computer? (e.g. in a weather station)

## Plenary

Students are to label a Raspberry Pi to include:

- all inputs (and where they connect to the Pi)
- all outputs (and where they connect to the Pi)
- processor
- storage (i.e. where the SD card goes)
- power.

This could be completed with sticky notes, a hand drawn diagram on paper, or on a computer using shapes and call out boxes.
