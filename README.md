# max-msp-math-pack
Max/MSP by Christian Yost for Mac OS

Included:

1. gcd external - computes the greatest common divisor of two integers
2. pfact external - computes the prime factorization of an integer
3. ratiofun - computes all possible ratios of an input list
4. log - like log~ but for floats

Please reach out with bugs/fixes to christianyost.0@gmail.com

http://www.christianyostdsp.com 

EDITS:

25.03.2019 - fixed an error message for cycle~ taking infinite frequency. When using the 		logarithmic frequency slide in alias mode, we simply need to add a conditional changing a zero going into the ‘log’ object to a one, so that we don’t return minus infinity.
