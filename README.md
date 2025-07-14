# MPXsensorsArduino
Various pieces of C code used for creating sensors for Multiplex M-Link Radio Control

This is to create a series of sensors for relaying information from a model aircraft to the pilot on the ground using the MPX M-Link system. It reads the information from a pressure sensor to an Arduino Mini Pro which places the data in a suitable string position along with sesnsor type and channel address before sending it to the R/C reciever. On the ground the pilot can see the results in realtime on a small LCD screen in an appropriate format.

The sensors chosen so far are Altitude (i.e. air pressure) and Voltage (onboard engine LiPo used for motor).
