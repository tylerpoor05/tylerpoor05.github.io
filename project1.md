[Back to Portfolio](./)

Senior Project
===============

-   **Class: Senior Project** 
-   **Grade: A** 
-   **Language(s): Python, Bash, and PowerShell** 
-   **Source Code Repository:** [Senior Project](https://github.com/tylerpoor05/SeniorProject)  
    (Please [email me](mailto:example@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

The project conisted of the building and implementation of a virtual network, the creation of a python-based exploit, and the development of a PowerShell based redmediation script. Each part of the program was manually ran by the tester to demonstrate a simulation of a real-world internal penetration test on a local network. 

## How to run the program

The program was run by a cli over a Kali Linux box that was on the internal network. It would connect to a server that had a known buffer overflow vulnerability on the network and would connect via a remote shell.

The attacker had to use msfvenom to create the shellcode for the exploit and then attach that to the source code before running "python3 overflow.py" over the command line.

The PowerShell remediation script would be run on the domain controller of the network. By changing registry settings and applying new group policy automatically, the script would remediate all vulnerabilities found during the penetration test.
