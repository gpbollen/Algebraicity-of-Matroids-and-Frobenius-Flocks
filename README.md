# Algebraicity-of-Matroids-and-Frobenius-Flocks
Sage files accompanying my PhD thesis

There are four Sage notebooks containing code to compute the conditions referred to in chapter 8:

-Dress-Lovasz and Ingleton-Main.ipynb
This file contains functions to compute the Dress-Lovasz and Ingleton-Main conditions for any matroid.

-Dress-Wenzel.ipynb
This file contains an implementation of the Tutte group by Rudi Pendavingh.
It can be used to check the Dress-Wenzel conditions

-Frobenius-flock representability of Matroids.ipynb
This file contains functions to check Frobenius-flock representability for a matroid. In doing so, it makes use of the sage object file "non2linearMatroidSet.sobj". Please make sure to change the 'path' variable in the notebook to the right directory.

-Valuations and Frobenius flocks from algebraic representations.ipynb
This file contains functions to compute the Lindstrom valuation and a Frobenius flock from an algebraic representation.

All four of these files have a common structure. First, the functions are given. Then, a number of examples is given, indicating how the functions are used to obtain the desired results.

Finally, there is a fifth notebook "Matroid Encyclopedia.ipynb". It fills up the entire matroid encyclopedia for all matroids up to 9 elements as best possible. Please follow the instructions in the notebook. Most ".sobj" files are used as data for this notebook. A completely filled matroid encyclopedia is also uploaded in 2 parts: MatroidEncyclopedia_part1.sobj, and MatroidEncyclopedia_part2.sobj.
