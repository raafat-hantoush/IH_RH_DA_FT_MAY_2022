

# numpy exercises

This is a collection of exercises that have been collected in the numpy mailing list, on stack overflow
and in the numpy documentation. The goal of this collection is to offer a quick reference for both old
and new users but also to provide a set of exercises for those who teach.


If you find an error or think you've a better way to solve some of them, feel
free to open an issue at <https://github.com/rougier/numpy-100>.
File automatically generated. See the documentation to update questions/answers/hints programmatically.

#### 1. Import the numpy package under the name `np` (★☆☆)
`hint: import … as`

#### 2. Create a null vector of size 10 (★☆☆)
`hint: np.zeros`

#### 3. Create a null vector of size 10 but the fifth value which is 1 (★☆☆)
`hint: array[4]`

#### 4. Create a vector with values ranging from 10 to 49 (★☆☆)
`hint: arange`

#### 5. Create a 3x3 matrix with values ranging from 0 to 8 (★☆☆)
`hint: reshape`

#### 6. Find indices of non-zero elements from [1,2,0,0,4,0] (★☆☆)
`hint: np.nonzero`

#### 7. Create a 3x3 identity matrix (★☆☆)
`hint: np.eye`

#### 8. Create a 3x3x3 array with random values (★☆☆)
`hint: np.random.random`

#### 9. Create a 10x10 array with random values and find the minimum and maximum values (★☆☆)
`hint: min, max`

#### 10. Create a random vector of size 30 and find the mean value (★☆☆)
`hint: mean`

#### 11. Create a 5x5 matrix with values 1,2,3,4 just below the diagonal (★☆☆)
`hint: np.diag`

#### 12. Normalize a 5x5 random matrix (★☆☆)
`hint: (x -mean)/std`

#### 13. How to find common values between two arrays? (★☆☆)
`hint: np.intersect1d`

#### 14. Create a random vector of size 10 and sort it (★★☆)
`hint: sort`

#### 15. Create random vector of size 10 and replace the maximum value by 0 (★★☆)
`hint: argmax`

#### 16. Subtract the mean of each row of a matrix (★★☆)
`hint: mean(axis=,keepdims=)`

#### 17. How to get the n largest values of an array (★★★)
`Z = np.arange(10000)
np.random.shuffle(Z)
n = 5
hint: np.argsort | np.argpartition`

#### 18. Create a random 5*3 matrix and replace items that are larger than 4 by their squares ( Example:  6 --> 36) 
`hint: np.where`
