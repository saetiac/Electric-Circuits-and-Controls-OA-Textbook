![EGR 311: Control Systems &
Instrumentation](media/image1.gif){alt="CI-formal-logo.jpg"
width="2.3025in" height="0.75in"}

Week#01 Laboratory Manual

# Contents {#contents .TOC-Heading}

[A.1 Pre-LAB Procedure [2](#pre-lab-procedure)](#pre-lab-procedure)

[A.2 Lab Objectives [3](#lab-objectives)](#lab-objectives)

[A.3 Lab Background [4](#lab-background)](#lab-background)

[A.4 Lab Procedures [9](#lab-procedures)](#lab-procedures)

[**A.4.1** **Part.1: Power Supply Voltage Measurement:**
[9](#part.1-power-supply-voltage-measurement)](#part.1-power-supply-voltage-measurement)

[**A.4.2** **Part.2: Voltage Divider Resistance, Current, and Voltage:**
[10](#part.2-voltage-divider-resistance-current-and-voltage)](#part.2-voltage-divider-resistance-current-and-voltage)

[A.5 Lab Deliverables [11](#lab-deliverables)](#lab-deliverables)

[A.6 Lab DDC (Optional-bonus) [11](#_Toc156297806)](#_Toc156297806)

Lab 01-A

## Pre-LAB Procedure

Going forward, almost all of your labs will have some basic pre-lab
bullets to complete BEFORE you come to class. These could include
reading some background and answering concept questions, completing
calculations, or even having a circuit build complete. There is no
pre-lab for this lab, but be sure to check Canvas for each lab's
write-up.

For this lab, you need to read the background section and watch the
instrumentation videos on Canvas.

## Lab Objectives

- Objectives

  - Introduce some of your equipment: DMM, Power Supply, Bread Board,
    cables

  - Familiarize yourself with your stations and safety

  - Get started building a simple circuit

- Learning Outcomes

  - Students will become familiar with their instrumentation

  - Students will able to complete simple circuits on their breadboard

  - Students will be able to demonstrate basic calculations of Ohm's Law
    and Kirchoff's Voltage Law (KVL).

## Lab Background

*Introduction*

In this lab, you begin to familiarize yourself with your stations and
some of the equipment available to you throughout the semester.

**The digital multi-meter (DMM)**

The digital multi-meter (DMM) is used to measure voltages, currents,
resistances and several other more complicated quantities. The DMM is a
relatively simple instrument, but incredibly useful for circuit analysis
and troubleshooting!

![A close up of a digital device Description automatically
generated](media/image2.png){width="6.5in" height="3.038961067366579in"}

Turn on the digital multi-meter by pressing the power button located to
the left on the front panel. To make the first measurement with the DMM,
first connect a pair of cables (see below for some options) to the DMM
(general rule: red = positive and black = negative). You will use the
other end to make your measurement. Which cable you choose will depend
on what and where you are measuring.

+----------------------------------------------------------+------------------------------------------------------+-----------------------------------------------------------+
| ![A black and red cable Description automatically        | ![Minigrabber 3782 Series Black,                     | ![A black and red cable with two black wires Description  |
| generated](media/image3.png){width="2.216965223097113in" | Red](media/image4.jpeg){width="2.1473206474190727in" | automatically                                             |
| height="2.201388888888889in"}                            | height="2.1473206474190727in"}                       | generated](media/image5.jpeg){width="2.101278433945757in" |
|                                                          |                                                      | height="2.0846653543307085in"}                            |
+:========================================================:+:====================================================:+:=========================================================:+
| Banana to Banana (left), Banana to Grabber (Middle), Banana to Alligator (Right)                                                                                            |
+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

**Voltage**

You can measure voltage with the DMM by selecting voltage as the
measurement option, the DMM will go into Auto-Range as a default, but
you can change this by clicking on the "Auto" button on the screen and
switching to whichever range you like. Unless you know what range to
expect, it is probably best to keep this in "Auto" until you know!

**Commons and Grounds**

Recall that voltage is a measure of the potential difference between two
points. Although we say, "the voltage at point A", we really mean "the
voltage at point A with respect to the local zero-potential reference
point."

The most useful zero-potential reference point is the earth itself---the
"ground." A ground in any circuit is defined to be any wire, lead, or
bus somehow connected to the earth. The power company thoughtfully
provides a wire connected to the earth in all three-pronged power
outlets (you cannot always assume that ground is connected, particularly
in older buildings), and that ground wire is often connected to a ground
lead in electrical equipment. Thus, the potential of a point in a
grounded circuit is the same as the potential difference between that
point and the earth.

Why do most electrical wall sockets have three leads? The electric
company intends current to flow between the hot and neutral wires in the
wall socket, the two rectangular slots. No current should flow in the
ground wire. The electric company arranges its transformers so that the
hot lead is approximately 120VRMS from the neutral, and the neutral is
approximately at ground. But things are rarely perfect, and the neutral
lead is often a few volts from ground. As for the ground lead itself
(the horseshoe shaped hole), the electric company grounds the lead by
actually attaching it to a long conducting rod stuck into the earth.
Look for the ground wire the next time you walk by a transformer on a
pole! Other good grounds are available. Cold water pipes, for example,
are well connected to the earth, and are often used as grounds.![A black
and white drawing of a power outlet Description automatically
generated](media/image6.png){width="1.3194444444444444in"
height="2.1694444444444443in"}

The electric company doesn't supply the ground as a courtesy for
electronic circuits builders; they supply it for shock prevention.
Electrical shocks occur when a sufficiently high voltage drives a
sufficiently high current through the victim's body. Most dangerous are
shocks in which current travels through the victim's heart; only 50mA
can be lethal. Grounding the outer case of a piece of equipment greatly
reduces the chance of shocks by shielding the user from any high
internal voltages.

It is difficult (but not impossible!) to get a serious shock with
voltages less than about 50V.

Caution: Standard electronic circuit construction always uses black for
ground, red for power and other colors for signal leads. BUT North
American building wiring always uses white for neutral, BLACK FOR HOT
(the dangerous lead) and green for ground, and various manufacturers use
different standards for wiring, it is wise to consult a manual for the
device in question before assuming a wiring convention.

*Aside: While grounding a circuit is usually beneficial, it is not
actually necessary. Cell phones, for instance, are not grounded. For
these circuits we define a "common" for the voltage---a local point that
all measurements on the circuit refer to. We will be revisiting this
concept throughout the semester.*

**Resistance**

*Be sure to disconnect the electronics component you wish to measure
from the circuit before making the resistance measurement* (think about
why it is better to do so). You also have two options for measuring
resistance. One is the standard 2 wire measurement (2W Ω) and the other
is a 4 wire measurement (4W Ω). The 4 wire measurement method is used
for measuring very small resistances when even the resistance in the
copper wire leads is important. Because this lab won't be dealing with
such low resistances, the majority of the measurements you make will be
done with the standard 2 wire method. To make the measurement, you can
hook up the banana plug to the correct red/black inputs for measuring
resistance, indicated by the Ω symbol, and select the 2 wire resistance
option indicated by the Ω symbol.

![A diagram of a multicolored band code Description automatically
generated with medium
confidence](media/image7.png){width="6.67650699912511in"
height="5.632883858267716in"}

**Current**

Current measurements also have two options: DCI and ACI. Consult the
picture below for how this is done.

When you measure current, you are measuring the current flowing through
a component (in this case, a resistor). Notice how the banana plugs are
inserted into the DMM and the orientation of the witch hat grabbers on
the resistor relative to the current flow to make the measurement. As
pictured, to measure current you must force the current to flow through
the DMM using your probes; usually, this is done by breaking the circuit
and inserting your DMM to the break.

![A close-up of a machine Description automatically
generated](media/image8.png){width="6.211034558180227in"
height="2.5375in"}

**Power Supply:**

Each station has a variable three channel power supply. You will connect
this to the breadboard using banana plugs from Channel 1. Next class
period we will explore the feature of current limiting your power
supply.

![A machine with wires and buttons Description automatically
generated](media/image9.png){width="4.555792869641295in"
height="3.409717847769029in"}

**Breadboard:**

Commercial electronic equipment is constructed on printed circuit
boards; "wires" are photo-etched onto a sheet of copper, and components
are soldered into place. To save time and effort, we will build our
prototype circuits on solderless breadboards, which are commonly used
for prototyping. A breadboard is an insulating board with a regular
pattern of holes that can be used as sockets. The sockets are
interconnected with hidden wires, and electronic component leads or
wires pushed into the socket holes will make contact with the
interconnecting wires below. The interconnecting wires on our
breadboards follow the pattern shown by the heavy lines in the drawing
below; the gray squares indicate the positions of the sockets.

*Tips for using your breadboard:*

- Use 22-gauge solid (not stranded) wire to make connections. Cut wire
  from your spool with about 3/8ths of an inch of stripped wire on each
  end to make sure you have a good connection. The breadboards are
  delicate! Forcing wires or component leads into the board can damage
  the sockets or make a poor connection. Wires or leads that do not fit
  easily into the breadboards may be too thick.

- Use the buses (the long strips) for power and ground connections. Good
  bus habits will save you lots of time and trouble with complicated
  circuits by making your circuit wiring more transparent and by
  removing unnecessary clutter.

- Build your circuits compactly. Long leads between components introduce
  stray capacitance and can result in oscillations or high frequency
  \[e.g., radio frequency (RF)\] pickup. · For clarity, signals should
  flow from left to right; place input signals on the left side of the
  board, circuitry in the middle, and output signals on the right side.

- Use color-coding to make your wiring clear: by convention, red wires
  are used for power connections, black wires are used for ground
  connections, and other color wires used for signals. Following this
  convention will help enormously when working with complex circuits
  later in this course and dramatically eases troubleshooting.

+--------------------------------------------------------------+--------------------------------------------------------------+
| > ![A close-up of a circuit board Description automatically  | > ![A black rectangular device with white and red buttons    |
| > generated](media/image10.png){width="3.1041666666666665in" | > Description automatically                                  |
| > height="2.5833333333333335in"}                             | > generated](media/image11.png){width="3.1041666666666665in" |
|                                                              | > height="2.3055555555555554in"}                             |
+--------------------------------------------------------------+--------------------------------------------------------------+
| Breadboards and a description of the connections - pay close attention to the solid blue (or black) and red lines that make |
| up the power rails. These are not always constant the entire length of the board! (images from Sparkfun.com)                |
+-----------------------------------------------------------------------------------------------------------------------------+

## Lab Procedures

*Equipment and Materials*

- Keithley Triple Channel DC Power Supply

- Keithley Digital Multimeter

- Makeronics breadboard

- Banana to banana; banana to witch hat cable leads

- Jumper wires

- Resistors (47 kΩ and 10 kΩ)

*Procedures, Results and Observations*

### **Part.1: Power Supply Voltage Measurement:**

Using your power supply and DMM, setup, measure, and record the power
supply voltages to your board for 24V, 12V, 5V, and 1.5V on the DMM.
Next measure the supply Voltage of a battery (variety available).

[**Q1 (10 PTs)** Record these values in the table below., Are these
precise? Why might they not be?]{.underline}

  ------------------ -------------------------
  Voltage            Measured Voltage

  24V                

  12V                

  5V                 

  1.5V               

  Battery            
  \_\_\_\_\_\_V      
  ------------------ -------------------------

**\**

### **Part.2: Voltage Divider Resistance, Current, and Voltage:**

![A diagram of a circuit Description automatically
generated](media/image12.png){width="4.973611111111111in"
height="1.479861111111111in"}

-Assemble this circuit on your breadboard! The resistor color code was
given previously in the lab and can be found at
https://en.wikipedia.org/wiki/Electronic_color_code.

**Q2 (15 PTs) \--**[With the power disconnected (turn power supply off),
measure and record the resistance of your resistors using the DMM. How
far off are these resistors? Typically, tolerance for resistors is ±
5%.]{.underline}

  ----------------------- ----------------------- -----------------------
  Resistor Value          Resistance Measurement  Calculated % Tolerance

  47kΩ                                            

  10 kΩ                                           
  ----------------------- ----------------------- -----------------------

**Q3 (20 PTs) \--**With the power connected, use your DMM to measure the
voltage at point A. Where does your negative lead go? What is your
measured voltage? provide statement on the difference between measured
and calculated (theoretical ) voltage?

**Q4 (15 PTs) -**-Swap the leads and measure the voltage again. What is
the difference?

**Q5 (20 PTs) -**- Measure the current through the 47kΩ resistor?
provide statement on the difference between measured and calculated
current?

**Q6** **(10 PTs)** \-- Calculate the voltage at point A if you swapped
the order of the resistors (10k then 47k). You can then rearrange your
circuit and remeasure the voltage at point A.

**Q7 (10PTs)** \-- What would the voltage at A be if the resistor values
were the same?

## Lab Deliverables

(All this week\'s lab deliverables should be combined and uploaded to
Canvas as a single PDF submission. The deadline is following Monday, at
the end of the day. This is an individual submission)

- Answers to questions in The Lab Procedure section.

- Highlight your answers in different color, and add graphs, figures,
  tables, and other resources as required. If the question involves
  calculations, make sure to sure your work.

- Don't forget to include **links** for any required Videos, documents,
  or photos as required (when applicable)
