# EXPERIMENT  01: ALP FOR 8086
### Name : Prajin S


### Roll no : 212223230151




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







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AX,1122H
MOV BX,2223H
ADD AX,BX
MOV [6000H],AX
```


## Output  
![Screenshot 2025-03-11 102139](https://github.com/user-attachments/assets/004d5dac-76fa-470e-bc3d-d710f0d50e1e)

 
## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AX,[5000H]
MOV BX,[5002H]
SUB AX,BX
MOV [6010H],AX
```
## Output  
![Screenshot 2025-03-11 102259](https://github.com/user-attachments/assets/052d1829-f9d2-4d8e-a7b2-b22790a83da0)

## Multiplication alp 
```
MOV AX,4444H
MOV AX,BX
MOV CX,3333H
MOV DX,CX
MUL DX
MOV [6020H],AX
```
 ## Output  
![Screenshot 2025-03-11 102317](https://github.com/user-attachments/assets/38ec4e75-6afd-4800-a0d8-fb94b574e815)


## Division alp 
```
MOV AX,702H
MOV BL,10H
DIV BL
MOV [6030H],AL
HLT
```

## Output  
![Screenshot 2025-03-11 103317](https://github.com/user-attachments/assets/a1d19e07-194e-408b-9007-695b3b21278c)

## Final Output
![Screenshot 2025-03-11 103345](https://github.com/user-attachments/assets/5b22403a-1026-4eda-80f4-dc6adfcd407a)

## AND of 8 bit numbers ALP
```
MOV AX,2122H
MOV BX,3451H
AND AX,BX
```
# Output
![Screenshot 2025-03-11 105314](https://github.com/user-attachments/assets/37ed1c11-f23f-4387-b054-0a9f86acee1b)

## OR of 8 bit numbers ALP
```
MOV CX,5614H
MOV DX,2346H
OR CX,DX
```
# Output
![Screenshot 2025-03-11 105326](https://github.com/user-attachments/assets/4c8156e9-b37c-460b-b9c2-3772faa35aa0)

## XOR of 8 bit numbers ALP
```
MOV AX,3546H
MOV CX,2381H
XOR AX,CX
```
# Output
![Screenshot 2025-03-11 105408](https://github.com/user-attachments/assets/2692abe4-12b1-4a5f-989d-c5b1e6052d79)

## NOT of 8 bit numbers ALP
```
MOV DX,4129H
NOT DX 
```
# Output
![Screenshot 2025-03-11 105418](https://github.com/user-attachments/assets/a4db8725-cf80-4be0-b83a-4c657ce3fd72)

## Result :
 
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.







