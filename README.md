# Thue-Morse-weave

The Thue–Morse sequence is an infinite sequence of 0s and 1s that is constructed by starting with 0 and successively appending the bitwise negation 
(interchange 0s and 1s) of the existing sequence. Here are the first few steps of this construction:

  0
  
  0  1
  
  0  1  1  0
  
  0  1  1  0  1  0  0  1
  
  0  1  1  0  1  0  0  1  1  0  0  1  0  1  1  0

To visualize the Thue–Morse sequence, create an n-by-n pattern by printing a + (plus sign) in row i and column j if bits i and j in the sequence are equal,
and a - (minus sign) if they are different.

![image](https://user-images.githubusercontent.com/100317918/211557867-ec7dee32-1eb7-43d8-9c48-ff1988b82613.png)


Note: you may assume that n is a positive integer (but it need not be a power of 2).

The Thue–Morse sequence has many fascinating properties and arises in graphic design and in music composition.
