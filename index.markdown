---
title: Marionette Open Source Data Acquisition (DAQ) System
layout: base
---

# Marionette Open Source Data Acquisition (DAQ) System 

## Overview

Marionette is an open hardware, firmware, and software project to bring expensive DAQ system features to the masses. It's 2015, so instead of some complicated weird FPGA or whatever, we can throw a regular old microcontroller at this problem and get "good enough" features. Features like:

- USB 2.1 High Speed performance
- Msps sampling performance
- Easy programming and firmware hacking for custom applications
- use standard USB classes, so we don't need weird drivers
 
Also, we wanted this to be heavily Python based, because we all use Python for prototyping because Python.

Finally, the name is K's fault. **Who** would name an awesome open project after creepy puppets?! <shudder>

## Why

We've all used things like [Labjacks](https://labjack.com/) and [Arduinos](https://www.arduino.cc/) for all of our DAQ before, and frankly, they're terrible. Arduinios are fast but slow and useless as soon as anything gets complicated, and Labjacks are spendy for good performance and despite being the industry standard and having an open API, they're just... weird. Their API is hard to understand and use, and there are weird drivers, and parts are open and other parts aren't... etc etc.

We wanted something reliable and fully open. That can do sophisticated things.

## Specifications

These are totally wrong, but here's what we started with:

 What               | How Much
 ----               | --------
 3.3V GPIO          | 60
 12 bit 1Msps ADC	  | 15
 12 bit DAC         |  5
 I2C interface      |  2
 CAN 2.0B interface |  1
 SPI	interface     |  1
 SD Card	           |  1

## Links

- [Link to hardware](https://github.com/marionette-daq/marionette-hardware)
- [Link to firmware](https://github.com/marionette-daq/marionette-firmware)
- [Link software](https://github.com/marionette-daq/marionette-software)
 
