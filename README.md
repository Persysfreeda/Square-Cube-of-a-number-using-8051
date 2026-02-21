# Square-Cube-of-a-number-using-8051
# 8051 Square  Program
# Name: Persys freeda J
# Reg no: 212224060185
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
MOV RO, #50H
MOV A, @Re
MOV B, @RE
MUL AB
INC RØ
MOV @RO,A
END
```

## OUTPUT
<img width="791" height="232" alt="image" src="https://github.com/user-attachments/assets/1caecfcd-6025-43f1-9710-db85ad17a622" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

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
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END
```


## OUTPUT
<img width="500" height="357" alt="image" src="https://github.com/user-attachments/assets/9ddd9b43-aabf-4e17-8521-c648632506ea" />
<img width="541" height="341" alt="image" src="https://github.com/user-attachments/assets/b9f07a59-8418-44f8-99ef-8104b39b07e5" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


