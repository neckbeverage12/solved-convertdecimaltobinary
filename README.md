Download Link: https://assignmentchef.com/product/solved-convertdecimaltobinary
<br>
5/5 - (1 vote)

prototypes for ConvertDecimalToBinary and PrintBinary

function ConvertDecimalToBinary()

pass in input decimal number and array to hold binary number (8 cells – 1 for each bit)

In for loop, use right bitshift to divide by 2

In for loop, use a bitmask to determine if odd or even and ternary if to assign 1 or 0 to bit array

function PrintBinary

pass in binary number array

Use for loop to print out each element of binary number arraymainInput loop

Ask for decimal number to convert

If entered number is not between 0 and 255,

then print “You entered a number not between 0 and 255” and ask for input again

If enterd number is between 0 and 255,

then leave input loop

Call ConvertDecimalToBinary()

Call PrintBinary()

Rubric

1.           CA2 uses 8 int variables to represent each bit of the binary number. CA3 should use an int array instead.

2.           Function ConvertDecimalToBinary() should have at least 2 parameters – the input decimal number and an array to hold the binary number.

3.           Function ConvertDecimalToBinary() should have a for loop that uses a right bitshift to divide by 2.

4.           Function ConvertDecimalToBinary() should have a for loop that uses a bitmask to determine if odd or even and ternary if to assign 1 or 0 to bit array5.           Function PrintBinary() should have at least one parameter – the array holding the binary number.

6.           Function PrintBinary() should use a for loop to print the binary number to the screen.

7.           Function main() should ask for a decimal number to be input. That input decimal number should be between 0 and 255.

If the input does not fit the range, then the input should be requested until it does fit the range. If 256 is entered, then user is prompted again for input

8.           Once a valid decimal number is input, function ConvertDecimalToBinary() and function PrintBinary should be called.9.           Converts decimal 0 to binary 00000000

10.         Converts decimal 1 to binary 00000001

11.         Converts decimal 255 to binary 11111111

12.         Converts decimal 170 to binary 10101010

13.         Compiles and runs