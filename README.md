# EEE3088F-Project
Power and Sensing repository for the EEE3088F Project. Group 24: RTHMAT004 and CLRMAT005

This repository contains files for both the sensing and power subsystems of a Micromouse for a university project. This project involved developing a Micromouse, therefore these solutions are built with existing systems in mind (microcontroller, servo motors etc). 

The power system deals with powering the two motors of the Micromouse, managing the charging of the battery and turning the Micromouse on and off.

The sensing system deals with surface detection around the Micromouse, inevitabely helping the micromouse navigate. The sensor does not make decisions of movement, or deal with any power control, it's only purpose is to detect objects and returning results using a voltage output signal. 

# Sensing subsystem:
The folder named "SensorKiCad-RTHMAT004" contains the KiCad files for the sensor subsystem. This subsystem solves the problem of sensing for the micromouse. This subsystem uses IR frequencies to detect objects within the bounds of the sensor. This subsystem solution should be used as a springboard for ideas surrounding sensing for devices such as a micromouse.  

# Power Subsytem
The folder named "PowerKiCad-CLRMAT005" contains the KiCad files for the power subsystem. This subsystem manages everything involving the powering of the Micromouse. This subsystem uses integrated circuits to control the motors and charging of the mouse. This subsystem solution should be used as a springboard for ideas surrounding the powering of small robotics.
