# pperm
A Classical [Boson Sampling] using the algorithm of Clifford and Clifford. Also provides functions for generating random unitary matrices, evaluation of matrix permanents (both real and complex) and evaluation of complex permanent minors.

The purpose of this project is 
parallelize the calculation of the matrix permanent with openMP to reduce the time complexity of the Boson Sampling problem:

![](https://latex.codecogs.com/gif.latex?%5Cmathcal%7BO%7D%28n2%5En&plus;poly%28m%2Cn%29%29)

where:

![](https://latex.codecogs.com/gif.latex?%5Cmathcal%7BO%7D%28n2%5En&plus;poly%28m%2Cn%29%29%20%3D%20%5Cmathcal%7BO%7D%28mn%5E2%29)


[Boson Sampling]: https://arxiv.org/pdf/1706.01260.pdf

