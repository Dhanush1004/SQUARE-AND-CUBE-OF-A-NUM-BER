
# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END

```

## OUTPUT
<img width="400" height="404" alt="image" src="https://github.com/user-attachments/assets/912335bd-fd13-418f-83ef-62d1e4f6bfb7" />
<img width="600" height="383" alt="Screenshot 2025-09-24 090244" src="https://github.com/user-attachments/assets/8e1b25f9-4791-4862-b7d5-20f24224fdd5" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
