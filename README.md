# How-to-make-Arduino-based-thread-winding-machine

![image](https://user-images.githubusercontent.com/19898602/185792078-c09fc67a-7eae-44d4-971d-8333e45a4fbc.png)


Hello friends in this video I have made a automatic thread winding machine using Arduino.

775 DC motor used to run the spool and stepper motor is used to slide thread guide mechanism.

I have also used one rotary encoder to calculate the length of thread wind to the spool. 

I have used one Nextion HMI from where User can give Input like how long thread need to be wind on spool in meter. 

after winding that exact length of thread on spool both motor will stop automatically.

# COMPONENT USED

1. Arduino Nano
2. [Multipurpose custom PCB](https://oshwlab.com/sharmaz747/multipurpose-pcb_copy_copy_copy)
3. 775 DC motor
4. A4988 Stepper driver
5. Nema 17 Stepper motors
6. Timing pulley
7. Timing belt
8. Linear rails
9. 3D printed parts 
10. Optical rotary Encoder
11. Some hardware 
12. Nextion HMI


![image](https://user-images.githubusercontent.com/19898602/185790845-8cf4fab1-6a78-4cc4-b12c-ecbda72b7d82.png)

![image](https://user-images.githubusercontent.com/19898602/185790687-afda25b6-3f2d-4f48-9a4e-2f9d702c0e9e.png)

First of all I have prepare the base of machine using 12mm wooden ply. and made the 8mm hole

at the four corner of the wooden sheet.

This 8mm hole is used to install the rubber legs. 

I also made the all corner round using my bench sander machine.

![image](https://user-images.githubusercontent.com/19898602/185790909-ead7cc36-36bc-45c5-8c66-c65379024b3a.png)

I then made the frame of 20x20 Alu. extrusion profile.

This frame is used to attached all the components of the machine. 

The main reason to use 20x20 alu. profile is its very easy to attach and dettach the components by just using the T nuts.


![image](https://user-images.githubusercontent.com/19898602/185791049-b752e615-c80e-4538-8154-261251576112.png)
![image](https://user-images.githubusercontent.com/19898602/185791062-5e400322-35ad-4388-a99e-da81fa1d4da4.png)


Then I use my home made CNC router to cut the 6mm Acrylic.

I made the to parts to hold the spool . 

there is a hole in acrylic part to place the bearing in it, then a SS shaft pass through it.

one end of this shaft is attached with timing pulley, 

Then I attached both acrylic part with 20x20 Alu. profile infront of each other.


![image](https://user-images.githubusercontent.com/19898602/185791213-d862008f-0c70-4e6f-ad2c-75c26739371c.png)
![image](https://user-images.githubusercontent.com/19898602/185791225-55f2e9d9-c99e-439c-8c21-348328131b6c.png)

Then I place a 775 DC motor on the one of the acrylic part. and secure it with the help of M4x10mm allen bolt.

Then I connect timming pulley on the both end of shaft and DC motor shaft.

I connect both timming pulley with the help if timing belt.


![image](https://user-images.githubusercontent.com/19898602/185791348-5cad33de-a0f7-46b8-adac-f2ebf1ab8964.png)
![image](https://user-images.githubusercontent.com/19898602/185791371-e527621b-5230-48f5-bf5a-6e8b016cd57b.png)

Then I design a 3D part so that I can install linear axis on it and, 8mm lead screw

I have place 8mm ID bearing on both 3D printed parts so that we can pass 8mm lead screw through it so that lead screw can rotate easily.

I have used 9mm linear bearing for left and right movement. this will used as thread guider for the machine.

![image](https://user-images.githubusercontent.com/19898602/185791597-bf126b81-239e-425e-9112-e5f811a83b80.png)
![image](https://user-images.githubusercontent.com/19898602/185791606-de13195b-0d4d-4fa0-88c2-267dcbfd6a5a.png)

Then I place 8mm timing pulley on the 8mm lead screw and place a Nema 17 stepper motor to run this lead screw.

I connected the lead screw and nema 17 stepper motor with the help of timing pulley.


![image](https://user-images.githubusercontent.com/19898602/185791685-6bd848ab-55b0-47e5-b526-d49ed7a7609c.png)
![image](https://user-images.githubusercontent.com/19898602/185791698-ce7fabbb-f8b0-464a-8bac-1cea59360499.png)


Here I have used a optical rotary encoder to count the lenght of thread wind to the spool. 

I used Orange 400 PPR 2-Phase Incremental Optical Rotary Encoder  
A rotary encoder is a type of position sensor which is used for determining the angular position of a rotating shaft. 

It generates an electrical signal, either analog or digital, according to the rotational movement.

Orange 600 PPR Incremental Optical Rotary Encoder is a hi-resolution optical encoder with quadrature outputs for increment counting. 

It will give 2400 transitions per rotation between outputs A and B. A quadrature decoder is required to convert the pulses to an up count. The Encoder is built to Industrial grade.


![image](https://user-images.githubusercontent.com/19898602/185791830-840591de-59d2-4163-9a0c-d918fba861c4.png)

![image](https://user-images.githubusercontent.com/19898602/185791841-e827a486-2742-49bb-81b8-27ab437a5030.png)


For this project I have used my multipurpose PCB this PCB can be used for so many projects. 

I have design circuit and PCB ineasy EDA and ordered PCB from [JLCPCB](https://jlcpcb.com/IAT )


[JLCPCB](https://jlcpcb.com/IAT ) are the world leader in PCB manufacturing there PCB production rates are very much affordable and they have world class PCB production unit results fast PCB production.

I have provided the link of circuit desgin so that you can modify it as per your need if you need to change any thing.

[Multipurpose custom PCB](https://oshwlab.com/sharmaz747/multipurpose-pcb_copy_copy_copy)



 ![image](https://user-images.githubusercontent.com/19898602/185792132-6d991caa-5e4c-4da9-88e1-d6110ecc5d05.png)
![image](https://user-images.githubusercontent.com/19898602/185792147-9360c677-95fd-4882-bc5e-beb40698c426.png)









