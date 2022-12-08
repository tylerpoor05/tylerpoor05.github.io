[Back to Portfolio](./)

CSCI-330 D Latch Verilog
===============

-   **Class: CSCI 330** 
-   **Grade: A** 
-   **Language(s): Verilog** 
-   **Source Code Repository:** [CSCI 330](https://github.com/tylerpoor05/CSCI-330)  
    (Please [email me](mailto:mtpoor@csustudent.net) to request access.)

## Project description

This program was designed to replicate a d latch used to store and move information on an electrical circuit board. It acts as a temporary buffer to sends bits across a line. This code is written in verilog and programs the latch to know what to do when the bits are sent to it. 

## How to run the program

The program is run using NASM to compile the verilog code. The ouput can then be seen using a IDE such as Visual Studio Code.

It would look like the following "nasm -felf64 "YourFile".v && gcc -no-pie -fPIC "YourFile".o && ./a.out

Fig 1.
![CSCI 330 Run Command](https://user-images.githubusercontent.com/65245471/206322873-4d169b9a-6107-4ae4-8a48-0ebb6968b7da.png)

Each input shows the four ways in which the d latch can move the bit along the wire.
![image](https://user-images.githubusercontent.com/65245471/206330624-822bcc28-ba88-4c4c-8e57-fa18620cc7eb.png)

The bits being sent over the wire can be seen in the output file a.out.
![image](https://user-images.githubusercontent.com/65245471/206334869-a5095b15-4c2a-44c2-8ccd-3bad43719469.png)
![image](https://user-images.githubusercontent.com/65245471/206335280-01ea00f7-8ca5-4f98-8edd-283065545f83.png)



