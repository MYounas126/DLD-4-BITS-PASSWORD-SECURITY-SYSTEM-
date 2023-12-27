# DLD-4-BITS-PASSWORD-SECURITY-SYSTEM-Project


Group Members:
Muhammad Younas (2022456)
Saad Ullah Khan Haidari (2022420)
Date of Submission: 19-December-2023



Table of Contents
Introduction
Project Description
Project Requirements
Block Diagram
Hardware Components Specifications
Proteus Schematics
Working Principle
Applications
Conclusion



Introduction

Security is a paramount concern in both residential and commercial settings. The 4-bit password security 
system presented in this report aims to provide a user-friendly and cost-effective solution for securing 
access to various applications, including doors, bank lockers, digital appliances, and switching systems. 
The system relies on a 4-bit password entry, requiring the user to input a specific combination for 
authorized access.


Project Description

The 4-bit password security system utilizes NOR and XOR gates in its design. The system consists of two 
sets of switches - "KEY CODE SWITCHES" representing the correct password and "DATA ENTRY 
SWITCHES" for entering the code. If the entered data matches the key code, the system allows access by 
lighting up a green LED. Conversely, if the data does not match, a red LED indicates an unauthorized 
attempt.


Project Requirements

The following components are required for the project:
4001 quad NOR gate
4070 quad XOR gate
Two four-position DIP switches
Two light-emitting diodes (LED)
Four 4007 "switching" diodes
Ten 10k ohms resistors
Two 470 ohms resistors
Pushbutton switch (normally open)
9-volt battery



Hardware Components Specifications


4001 Quad NOR Gate:

Used to perform logical NOR operations in the circuit.

4070 Quad XOR Gate:

Performs exclusive OR operations, crucial for password validation.


Four-Position DIP Switches:

Represent the "KEY CODE SWITCHES" and "DATA ENTRY SWITCHES."


Light-Emitting Diodes (LEDs):

Two LEDs indicate access status - green for authorized access and red 
for unauthorized attempts.


4007 "Switching" Diodes:

Essential for signal routing and preventing feedback.


Resistors:

Ten 10k ohms resistors and two 470 ohms resistors for proper current limiting.

Pushbutton Switch (Normally Open):

Used for system reset or other control functions.


9-Volt Battery:

Power source for the circuit.


Working Principle

The XOR gates compare the entered data with the key code, and the NOR gates generate output signals 
based on the comparison results. The green LED indicates a correct password match, while the red LED 
signals an incorrect attempt.


Applications

Locking of Doors:

Provides a secure and cost-effective door locking system.
Bank Lockers: Enhances security for individual bank lockers.


Digital Appliances:

Used for password-protected access to devices like mobile phones, computers, 
laptops, and tablets.


Switching Systems:

Applied for secure switching of appliances such as air conditioners, LEDs, and TVs.


Conclusion


The 4-bit password security system offers a practical and effective solution for enhancing security in 
various applications. It's simple design and reliable operation make it suitable for both residential and 
commercial settings
