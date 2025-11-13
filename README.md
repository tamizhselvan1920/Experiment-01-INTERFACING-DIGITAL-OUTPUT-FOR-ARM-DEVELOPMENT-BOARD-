
# EXPERIMENT-01 ALP FOR FUNDEMENTAL ARITHMETIC AND LOGICAL OPERATIONS ON 8086 EMULATOR
## Name :THAMIZH SELVAN R
## Roll no : 212222230158






## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
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
MOV AX, 4043H
MOV CX, 3039H   
ADD AX,CX
RET
```
## Output  

<img width="1178" height="1035" alt="Screenshot 2025-08-19 085609" src="https://github.com/user-attachments/assets/f194d564-c866-43b9-80d3-be4ff1290761" />



 
## Subtraction   of 8 bit numbers  ALP 
```
MOV AX, 3049H
MOV BX, 2039H   
SUB AX,BX
RET
 ```
## Output  

<img width="1246" height="1067" alt="Screenshot 2025-08-19 085911" src="https://github.com/user-attachments/assets/c50c87ad-c4fb-4939-841d-424e215c4f8e" />


## Multiplication alp 
```
MOV AX, 3049H
MOV BX, 2039H   
MUL AX
RET
```
 ## Output  
 <img width="1249" height="1055" alt="Screenshot 2025-08-19 090004" src="https://github.com/user-attachments/assets/1996de67-18a7-4829-a7ed-f5a152e092f3" />




## Division alp 
```
MOV AX, 3049H
MOV BX, 2039H   
DIV AX
RET
```

## Output  
<img width="1223" height="1067" alt="Screenshot 2025-08-19 090032" src="https://github.com/user-attachments/assets/81178e0c-c5d4-463c-9e36-4cfcb7268d55" />


## Programs for Logical operations

## Logical bit numbers

```
org 100H
MOV AX, 4535H
MOV BX, 733FH   
AND AX,BX 
MOV [2000H],AX 


MOV AX, 4535H 
MOV BX, 733FH    
OR  AX,BX
MOV [2002H],AX 


MOV AX, 4535H 
MOV BX, 733FH    
XOR AX,BX
MOV [2004H],AX 


MOV AX, 4535H  
NOT AX
MOV [2006H],AX   


RET

```


## Output

<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/d7823390-b938-4009-ba6b-fabb7e697782" />



## Result :

 The execution of ALP on fundemental arithmetic and logical operations executed successfully.
