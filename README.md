# ATARIPC1_RTC
A real time clock for the Atari PC1 using the Dallas DS1315-5 chip

This project creates a moden day replacement for the Dallas DS1216E real time clock IC that was used as a way to add an RTC to IBM-PC and compatible computers.

The original Dallas DS1216E incorporated a DS1216 clock chip, a 32.768Khz oscillator and a 3V battery into a single enclosure that was designed to be installed under one of the 28-pin ROM ICs.  

The DS1216E included the ability to insert the displaced ROM IC into the DS1216E with pass-thru for all pins.  

SmartWatch software was written for the PC to use the DS1216E to store and set the PC's clock upon startup.  

The DS1216E is no longer available.  All existing units now have expired batteries which cannot be replaced. This project recreates the DS1216E using modern parts and an externally connected battery that can be easily replaced.

NOTE:  Since completing the project I have realized the user jdos has also recreated the DS1216E with a focus on Tandy PC compatibles, and did so before my work on this project.   The solutions are very similar.
