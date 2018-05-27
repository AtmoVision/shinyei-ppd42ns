# shinyeippd42ns
This code was modified from Matthew Schroyner's code to create a PM 2.5 sensor.

One major change with this code was the change of threshhold voltage by using a resistor across Pin 5 on the sensor and reading off of P2 (pin 2) on the sensor instead of the P1 (pin 4).

The idea to add a 10k resistor was taken from here: https://indiaairquality.com/2014/12/14/measuring-the-pickle-jr-a-modified-ppd42-with-an-attached-fan/.  This website is run by a young scientist who goes by the name "AJ".  AJ also pointed to a reverse engineering of the PPD42NS that was done by Tracy Allen, which can be viewed here: http://takingspace.org/wp-content/uploads/ShinyeiPPD42NS_Deconstruction_TracyAllen.pdf.

This code is the code used for the PM 2.5 sensor project that is described at 
https://airquality406.wordpress.com/
