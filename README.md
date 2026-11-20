# EXPERIMENT--01-ALP-FOR-8086
## Name :BRINDHA A R
## Roll no :212225040050
## Date of experiment :20/11/2026





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations (16 bit)
```

Mov AL,74H
MOV BL,69H
ADD AL,BL
HLT

Mov AL,74H
MOV BL,69H
SUB AL,BL
HLT

org 100h
Mov AL,74H
MOV BL,69H
MUL BL
HLT
ret

MOV AL,68H
MOV BL,18H
DIV BL
HLT

```


## Output  

<img width="1917" height="1078" alt="Screenshot 2026-10-30 183806" src="https://github.com/user-attachments/assets/df0e657a-a9ac-41cd-b8b4-e99ff7d40690" />

<img width="1917" height="1078" alt="Screenshot 2026-10-30 183834" src="https://github.com/user-attachments/assets/16915f2f-7b0f-4e0d-b177-f96c407fed4f" />

<img width="1917" height="1078" alt="Screenshot 2026-10-30 183901" src="https://github.com/user-attachments/assets/35eee0df-715d-4fd8-a3e4-dda42ea8dee0" />

<img width="1917" height="1078" alt="Screenshot 2026-10-30 183926" src="https://github.com/user-attachments/assets/df92f5c4-5e31-47eb-9bc9-21c4f7a84394" />


## Programs for logical  operations (16 bit)

```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT

MOV AL,45H
MOV BL,66H
OR AL,BL
HLT

MOV AL,65H
NOT AL
HLT

MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```
## Output  

<img width="1917" height="1077" alt="Screenshot 2026-10-30 183951" src="https://github.com/user-attachments/assets/f085d884-0e6c-4c89-a7b1-e63c225a2e91" />

<img width="1917" height="1078" alt="Screenshot 2026-10-30 184012" src="https://github.com/user-attachments/assets/8ffd7986-3106-423c-ad66-cd1b8f52617a" />

<img width="1917" height="1078" alt="Screenshot 2026-10-30 184035" src="https://github.com/user-attachments/assets/7f57200a-ad62-44d9-9a52-9aea7b6247d4" />



## Result :
 

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.







































.


































































































..


















































































































































































































































...




