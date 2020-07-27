# Simple-2-3-5-7-11-13-Factorization
Simple 2,3,5,7,11,13 Factorization

This is a simple program that uses number tricks to determine whether a number is divisible by either 2,3,5,7,11 or 13.
Using arrays we can do rather large numbers.

I have tested this rather extensively and see no problems with the code. Feel free to let me know of any errors apart from the way I layout my code - I like to see a lot of code on a page for readability. I'm aware not everyone likes bunched up code, I do - no apologies.

To test for divisibility of 2 and 5 we take the last digit and determine whether it is divisble by a simple subtraction process.
To test for 3 we take the digital root and determine whether it is divisible by 3. In other incarnations of this idea 9 is subtracted periodically (when the accumulative sum is equal to or over 9) to minimise the amount of division at the end. This is done with the number 1001 in the 7,11,13 process, it is divisble by 7,11 and 13. Another version has the number going through the initial process again to cut down the amount of digits if it is over 999.

To test for 7,11,13 divisibility we take groups of three digits,create a number out of them (by multiplying by the appropriate power of ten and addition - 3 2 1 becomes 3*100+2*10+1) and alternatively add and subtract these numbers to create final number. The idea with this and the other test is to minimise the amount of digits one does the final "division" count on.

This module was designed to be used on another one of my projects that determines the prime nature of a number by using other number tricks without direct use of the / or % operators in C.

There will be other projects exploring this theme.
