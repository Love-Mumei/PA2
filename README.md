# ECE2112-PA2
* Kyle Nathaniel Dimalanta
* 2ECE-C
* 08/30/24

# Problems:
## 1. Normalization Problem:
* The problem requires me to generate a 5 x 5 matrix with random numbers
* After generating the matrix of random numbers, I normalized the values and saved it in "X_normalized.npy"
* Lastly, I printed the original Values in the matrix and the Normalized Values.

## 2. Divisible by 3 Problem:
* In this problem, I need to create a 10 x 10 array of squared numbers 1 - 100 and list and save the result as "div_by_3.npy".
* The first thing I did was create a list that created a list of 1 - 100.
* after creating the list I converted the list into a 10 x 10 array by using .reshape(10, 10).
* The next step is that I squared the array using np.squared().
* After squaring all the numbers, I checked for the numbers where if the number divided by 3 has a remainder of 0, it will be added to the list.
