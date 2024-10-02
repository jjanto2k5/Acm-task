documentation:

• c = 0: A counter variable c is initialized to zero. 

• The function uses a for loop that runs 32 times (for i in range(32):). This is because the function assumes n is a 32-bit integer

•  c += n & 1: This expression checks if the least significant bit (rightmost bit) of n is 1. The bitwise & operator compares the least significant bit of n with 1. If it is 1, it increments the counter c by 1.
