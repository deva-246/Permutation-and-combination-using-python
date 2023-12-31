# Permutation-and-combination-using-python

Permutations and combinations, the various ways in which objects from a set may be selected, generally without replacement, to form subsets. This selection of subsets is called a permutation when the order of selection is a factor, a combination when order is not a factor. By considering the ratio of the number of desired subsets to the number of all possible subsets for many games of chance in the 17th century, the French mathematicians Blaise Pascal and Pierre de Fermat gave impetus to the development of combinatorics and probability theory.

The concepts of and differences between permutations and combinations can be illustrated by examination of all the different ways in which a pair of objects can be selected from five distinguishable objects—such as the letters A, B, C, D, and E. If both the letters selected and the order of selection are considered, then the following 20 outcomes are possible:
List of the 20 potential combinations of the letters A, B, C, D, and E.

![image](https://github.com/deva-246/Permutation-and-combination-using-python/assets/75877347/b4aeafff-c5fc-42f0-a24d-801baee0135a)

Each of these 20 different possible selections is called a permutation. In particular, they are called the permutations of five objects taken two at a time, and the number of such permutations possible is denoted by the symbol 5P2, read “5 permute 2.” In general, if there are n objects available from which to select, and permutations (P) are to be formed using k of the objects at a time, the number of different permutations possible is denoted by the symbol nPk. A formula for its evaluation is

nPk = n!/(n − k)!

The expression n!—read “n factorial”—indicates that all the consecutive positive integers from 1 up to and including n are to be multiplied together, and 0! is defined to equal 1. For example, using this formula, the number of permutations of five objects taken two at a time is

![image](https://github.com/deva-246/Permutation-and-combination-using-python/assets/75877347/156cfc84-bc65-42f4-8453-a8f2ec9439db)


(For k = n, nPk = n! Thus, for 5 objects there are 5! = 120 arrangements.)

For combinations, k objects are selected from a set of n objects to produce subsets without ordering. Contrasting the previous permutation example with the corresponding combination, the AB and BA subsets are no longer distinct selections; by eliminating such cases there remain only 10 different possible subsets—AB, AC, AD, AE, BC, BD, BE, CD, CE, and DE.

The number of such subsets is denoted by nCk, read “n choose k.” For combinations, since k objects have k! arrangements, there are k! indistinguishable permutations for each choice of k objects; hence dividing the permutation formula by k! yields the following combination formula:

![image](https://github.com/deva-246/Permutation-and-combination-using-python/assets/75877347/a0fd1122-381e-45f8-a446-eea57e722930)

This is the same as the (n, k) binomial coefficient (see binomial theorem; these combinations are sometimes called k-subsets). For example, the number of combinations of five objects taken two at a time is

![image](https://github.com/deva-246/Permutation-and-combination-using-python/assets/75877347/51bbf738-2bfd-437f-b5df-13d2943d4ab7)


The formulas for nPk and nCk are called counting formulas since they can be used to count the number of possible permutations or combinations in a given situation without having to list them all.



