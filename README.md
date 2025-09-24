# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```

## OUTPUT
<img width="566" height="495" alt="image" src="https://github.com/user-attachments/assets/35192681-f9fe-4702-bc35-c9ad31e303ae" />
<img width="648" height="339" alt="image" src="https://github.com/user-attachments/assets/c2c805b8-815a-4c13-b356-0c4b69b656a1" />

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.
