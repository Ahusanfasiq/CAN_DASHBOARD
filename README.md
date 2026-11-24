# CAN-Based Automotive Dashboard

## Project Overview

The CAN-Based Automotive Dashboard is an embedded systems project that
demonstrates communication between multiple Electronic Control Units
(ECUs) using the Controller Area Network (CAN) protocol.

The project uses three PIC18F4580 microcontrollers configured as
separate ECUs to simulate an automotive communication system. Each ECU
performs a specific function, and vehicle-related data is exchanged
through the CAN bus and displayed on a 16×2 character LCD.

The main objective is to understand multi-ECU communication, CAN message
transmission and reception, and vehicle data monitoring in an automotive
embedded system.

## System Architecture

The project consists of three ECUs:

  -----------------------------------------------------------------------
  ECU                                 Function
  ----------------------------------- -----------------------------------
  ECU 1 -- Input ECU                  Reads input data from sensors or
                                      input devices

  ECU 2 -- Engine ECU                 Processes vehicle-related data and
                                      communicates through CAN

  ECU 3 -- Display ECU                Receives CAN messages and displays
                                      information on the LCD
  -----------------------------------------------------------------------

## Hardware Components

-   PIC18F4580 microcontrollers (3)
-   CAN transceiver modules
-   16×2 character LCD
-   Input devices / sensors
-   CAN bus connections
-   Connecting wires and power supply

## Communication Protocol

**Controller Area Network (CAN)**

-   CAN 2.0 communication
-   11-bit standard identifier
-   Message-based communication
-   Multi-ECU data exchange
-   CAN message transmission and reception

## Working Principle

1.  The Input ECU collects vehicle-related input data.
2.  The collected data is transmitted through the CAN bus.
3.  The Engine ECU processes vehicle-related data and exchanges
    information through CAN communication.
4.  The Display ECU receives the required CAN messages.
5.  The received information is displayed on the 16×2 LCD.
6.  All three ECUs communicate through the shared CAN network.

## Software and Development Tools

-   Embedded C
-   MPLAB X IDE
-   XC8 Compiler
-   PIC18F4580 microcontroller
-   CAN protocol

## Key Features

-   Multi-ECU communication architecture
-   CAN-based data transmission and reception
-   11-bit standard CAN identifier
-   Data exchange between multiple ECUs
-   LCD-based vehicle parameter display
-   Modular embedded system design

## Learning Outcomes

-   Understanding automotive CAN communication
-   Working with PIC18F4580 microcontrollers
-   Implementing CAN message transmission and reception
-   Understanding multi-ECU architecture
-   Developing embedded C applications
-   Interfacing a character LCD and input devices

## Project Objective

To develop a simplified automotive dashboard that demonstrates how
multiple ECUs communicate and exchange vehicle-related information using
the CAN protocol.

## Author

**Ahusan Fasiq R.**

GitHub: [Ahusanfasiq](https://github.com/Ahusanfasiq)

------------------------------------------------------------------------

*This project was developed as part of Embedded Systems learning to gain
practical experience in automotive embedded systems and CAN
communication.*
