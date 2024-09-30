documentation

steps:

৹ This variable ans will store the final result after reversing the bits.

৹  The for i in range(32) loop iterates 32 times, which is the number of bits in a standard 32-bit integer. For each iteration, the code checks and shifts individual       bits from n to their reversed position in ans

৹ This expression checks if the i-th bit of n is set (i.e., whether it's 1).n >> i shifts n to the right by i bits, moving the bit in the i-th position to the least 
  significant position.& 1 masks all bits except the least significant bit, effectively checking if the bit at position i is 1.
