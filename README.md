# primeNumberGenerator
Function that generates prime numbers

import math
def generatePrimeNo(n): # function to generate prime numbers
    if n == 0 or n == 1:
        return False
    for x in range(10, n): # using 10 as test number in range
        if n % x == 0:
            return False
    else:
        return True
