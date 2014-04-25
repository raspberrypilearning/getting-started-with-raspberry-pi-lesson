## Lesson 1 - Getting started with Raspberry Pi

###Introduction

The Raspberry Pi is a tiny computer less than the size of a pack of cards which can transform the way we perceive and approach computation. In this lesson we will introduce the basic components of the Raspberry Pi and how they relate to a traditional computer. We will discuss the generic nature of computation and how the same computer can be programmed to simultaneously do many different things - from word processing to music synthesis. Finally, we will introduce the most basic principle of programming - a program as a sequence of instructions.

### Learning Objectives

- Know the basic architures of a computing device.
- Understand the difference between hardware and software.
- Be able to set up a Raspberry Pi, turn it on, load the graphical user interface and navigate the desktop for the first time.

### Learning Outcomes

**All students are able to:**

- Plug the components of a RPi together.
- Understand that computers are general-purpose devices and not every computer is obviously a computer.
- Indentify basic architecture of a computer: processor, storage, input/output

**Most students are able to:**

- Set up a Raspberry Pi for the first time, log in, and load the graphical user interface.
- Identify different types of computers and explain what makes them a type of computer.
- Understand basic architecture of a computer: processor, storage, input/output

**Some stufents are able to:**
- Set up a Raspberry Pi, log in, load the graphical user interface without assistance.
- Explain with examples the similarities and differences of a Raspberry Pi compared with a personal computer. 

### Lesson Summary

- An introduction to the basic physical parts of a RPi
- An introduction to two types of computer interface
	- command line
	- graphical

### Starter
Distribute the [computing device cards](Computing-Device-Card-Sort.zip) to paris of students. Ask them to match the device to the description. Then ask students to create two piles: one for devices that they think are a type of computer, and one for devices they do not think are types of computers. 

After a few minutes discuss the outcomes of this task with the class. Note that all the cards are types of computing devices! Draw on students answers to discuss what makes a computer.

### Main Development:
1. Watch the [‘What is a Raspberry Pi?’ offical animation](http://www.youtube.com/watch?v=e0wkVVVLvR8)  

2. Start with all the parts of the Raspberry Pi on a table: 
	- keyboard, 
	- mouse, 
	- SD memory card, 
	- power supply, 
	- monitor, 
	- monitor cable and 
	- Raspberry Pi itself. 
	
	Ask the class to name and describe each component as you connect it to the RPi in front of the class. 

	Explain that these components are **hardware**. Hardware refers to the physical elements of the computer that you can see and touch. This includes what is sometimes hidden inside the case. 

	Finally, plug in the power and watch it boot up. An alternative to this demonstration is to leave out the memory card and try and boot it to no avail. It should then be possible to describe the memory card as something that contains instructions to tell the RPi how to start.

2. Demonstrate that the Raspberry Pi is a **standard** computer by opening up some applications and closing them again. If you are able to connect the RPi via a network connection, then open up a web browser and surf to a couple of different sites.

	Explain that this is software. Software is the term given to programs that run on the computer system. Programs are what make the hardware work. For example, by making a calculation or organising files. There are two main types of software: system software which runs and manages your computer and application software which performs a specific task or function.

3. Distribute equipment to students and ask them to set up their own Raspberry Pis. Distribute the power supplies last, checking that students have connected their cables and SD cards correctly before they are powered up.

4. Ask students to log into their Pis for the first time using:

	```
	Login: pi
	password: raspberry
	```

	Please note that students will not see any text when typing the password but rest assured it is working. Ask students why this might be the case? *Hint: What might happen if someone was looking over your shoulder?*

	Once logged in, explain to the students that they can give instructions to the Raspberry Pi using the **command line interface**.

5. Load the graphical user interface by typing `startx`

	Explain the students that they have now loaded the **Graphical User Interface** or GUI of the operating system. Ask them to identify any parts that they recognise, for example, the desktop, task bar, menu system, mouse pointer, icons, etc. 

6. As an exstention task, ask students to compare a Raspberry Pi to a desktop computer. What are the similarities. What are the differences? In what situations could you use a Raspberry Pi instead of a desktop computer? (e.g. in a weather station)

##Plenary

Distribute the label a Raspberry Pi worksheet and ask students to complete the labelling of the Raspberry Pi to include:
- all inputs (and where they connect to the Pi)
- all outputs (and where they connect to the Pi)
- Processor
- Storage (i.e. where the SD card goes)
- Power 

