
1. Write a Program to add two 8-bit numbers using 8085 Microprocessor. 



|Address |Opcode |Hexcode |Hexcode |Label |Instructions |
| - | - | - | - | - | - |
|8000 |21 |00 |85 ||LXI                    H,8500 |
|8003 |7E ||||MOV                A,M |
|8004 |23 ||||INX                   H |
|8005 |46 ||||MOV                B,M |
|8006 |80 ||||ADD                 B |
|8007 |32 |00 |90 ||STA                  9000 |
|800A |76 ||||HLT                -   |

INPUT:                                                            

First Number:  8500  Second Number:  8501

 



Resources:

https://youtu.be/RPYxXPYUGJ4
