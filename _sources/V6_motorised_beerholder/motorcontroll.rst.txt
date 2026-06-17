Motor controll
===============

This page will demonstrate what components were used in  the motor block, including the motor controller and the DC-motor. This aspect of the assembly and how the components are connected together in a circuit diagram. 
while also going through the process on how and why we did certain things when connecting everything together. As well as what one should think about when doing this on your own.


In this project we used an CJMCU-7960 motorcontroller to reduce the voltage input to the motor. Seeing as 12 V on the motor would simply make the rotation
axel spin to fast and reduce the fizzyness of the beverages. While testing we concluded that 7V would be useful for our system. 


How each pin is connected on the controller is represented in the figure below. 


.. figure:: ../_static/V6_motorised_beerHolder/Kretsskjema_motor_motorkontroller_ESP32.png
   :align: center
   :height: 600
   :width: 600 

   Representation as the circuit analysis for motorcontroll