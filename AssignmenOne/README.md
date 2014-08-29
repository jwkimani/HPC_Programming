Question One
============
Suppose the run-time of a serial program is given by Tserial = n^2, where the units of the run-time are in microseconds.
Suppose that a paral- lelization of this program has run-time Tparallel = n^2/p + log2(p). Write a program that finds the 
speedups and efficiencies of this program for vari- ous values of n and p. Run your program with n = 10,20,40,...,320, 
and p=1,2,4,...,128. What happens to the speedups and efficiencies as p is increased and n is held fixed? What happens when 
p is fixed and n is increased?

Question Two
============
SupposethatTparallel=Tserial/(p+Toverhead.Also suppose that we fix p and increase the problem size.
- Show that if Toverhead grows more slowly than Tserial, the parallel efficiency will increase as we increase the problem size.
- Show that if, on the other hand, Toverhead grows faster than Tserial, the parallel efficiency will decrease as we increase the problem size.
