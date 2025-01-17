# BCMO_Package_Python
- We contribute an updated Python version of BCMO Package provided in https://github.com/ThangLe-duc/BCMO_Package. In this package, we introduce an upgraded version named Balancing Composite Motion Optimization with Gaussian Random Walk (GRW-BCMO). The corresponding Matlab version of GRW-BCMO is also provided as the release v1.1 of BCMO package in https://github.com/ThangLe-duc/BCMO_Package/releases/tag/v1.1.
- In GRW-BCMO, we modify the trial mechanism for determining the instant global point and the best individual via a Gaussian random step biased from the current best individual to exploit its local space. This version will solve the boundary dependency of the original trial mechanism proposed in the previous one. The proposed algorithm is constructed without algorithm-specific parameters, the users can directly apply it to solve any unconstrained optimization problems without hyperparameter tuning.
- The users are recommended to use Python 3.7 or more. The required libraries for using this package is numpy and matplotlib. The users can easily follow the examples with detailed instructions to implement and modify the codes for personal uses. 
# Contributors:
- Thang Le-Duc
- Quoc-Hung Nguyen
- Hung Nguyen-Xuan 
# References:
- Please cite the following reference if the package is useful for your project:
- Thang Le-Duc, Quoc-Hung Nguyen, H. Nguyen-Xuan, Balancing Composite Motion Optimization, Information Sciences, in press, 2020 https://www.sciencedirect.com/science/article/pii/S0020025520300773
