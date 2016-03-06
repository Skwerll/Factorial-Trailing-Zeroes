# Factorial-Trailing-Zeroes
Python code that finds the number of trailing zeroes in the factorial of an inputted number.

import math

i = int(raw_input())

def FactorialZeroes(i):
	n = math.factorial(i)
	a = str(n)
	return (len(a) - len(a.rstrip("0")))
	


print FactorialZeroes(i)
