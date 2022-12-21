# ALU 16-Bit

In computing, an ALU (Arithmetic Logic Unit) is a combinational digital circuit that performs arithmetic and bitwise operations on integer binary numbers.
It is a fundamental building block of many types of computing circuits, including the CPU of computers, FPUs, and GPUs.

The inputs to an ALU are the data to be operated on, called operands, and a code indicating the operation to be performed; the ALU's output is the result of the performed operation.
This ALU receives two operands of integer binary numbers of 16 bits. It receives one operation code to be performed. It output the result of it.

List of Operations:
0. addu: adds two unsigned numbers
1. subu: substract two unsigned numbers
2. and: takes two numbers and produces the conjunction of them
3. or: takes two numbers and produces the union of them.
4. not: looks at the first number and turns every 1 into a 0 and every 0 becomes a 1.
5. xor: behaves like regular OR, except it’ll only produce a 1 if either one or the other numbers has a 1 in that bit-position.
6. lui:  loads the highest 8 bits of the number, and clears the lowest 8 bits to 0s.
7. sltu: check if first unsigned number is less than the second unsigned number
8. add: adds two numbers
9. sub: substracts two numbers
15. slt: check if first number is less than the second one


Open JLS Program:

```
java -jar JLS.jar ALU_16Bit.jls
```

Run test on JLS Program:

```
java -jar DLUnit.jar ALU_16Bit.jls Sample16BitALUtest.class
```
