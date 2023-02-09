## Casio BASIC Programs - MOD, REMAIN & VENN

Simple programs, not really doing anything particulary groundbreaking, just meant to save a bit
of time working out where applicable.

* MOD - Find the least residule of a number given it's MOD value.
* REMAIN - Divide a number by another, and recieve it's total divisible amount and remainder left over.
* VENN - Aids in the solution of 3-circle venn diagram problems.

### Background

Developed for use in ECU's computer fundamentals unit, may also be of use for similar maths-based 
units in other computer science courses.

### MOD Program notes

Made for quicker calculation of least residule values.
- Asks for a number, and then asks for it's MOD value.
- Returns least residule value.

### REMAIN Program notes

Made for use in manually working out conversion between certain number systems (eg. Dec -> Hex)
- Asks for a number, and then asks for a value to divide the number by.
- The program then first returns the number of times the number can be divided (without ending up with
a fraction)
- After pressing EXE a second time, the program returns the remainder left over after the division
takes place.
- Finally, the program asks if you would like to divide another number. 1 for yes, 0 for no.

### VENN Program notes

Made for quicker solving of 3-circle venn diagram problems.

The program labels your circles as A,B,C.
- Inputs in order:
	1. Universe amount
	2. Amount outside circles
	3. Total of A
	4. Total of B
	5. Total of C
	6. Total of AnB
	7. Total of AnC
	8. Total of BnC
	
- The program then returns outputs in order:
	1. Number of AnBnC (X)
	2. Number of AnB-X
	3. Number of AnC-X
	4. Number of BnC-X
	5. Only A
	6. Only B
	7. Only C
