This directory includes test instances for TSP-D, which first appeared in the following paper:

- Bogyrbayeva, A., Yoon, T., Ko, H., Lim, S., Yun, H. and Kwon, C., 2022. A Deep Reinforcement Learning Approach for Solving the Traveling Salesman Problem with Drone. *Transportation Research Part C: Emerging Technologies*, To appear. https://arxiv.org/abs/2112.12545


# `Random`

There are three files of three sizes `n=20, 50, 100`. 
Each file contains 100 test instances of the same size.

Each row represents a test instance with 100 coordinates.
We follow the format of  
```
x1 y1 x2 y2 ... xn yn
```
where `x1 y1` are for the depot.


# `Amsterdam`

The same format is used for four different sizes `n=10, 20, 50, 100`.

For a detailed description of how these instances are generated, please refer to [Bogyrbayeva et al. (2022)](https://arxiv.org/abs/2112.12545).


See also [TSPDrone.jl](https://github.com/chkwon/TSPDrone.jl).