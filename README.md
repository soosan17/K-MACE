# K-MACE and Kernel K-MACE Clustering
## Abstract
Determining the correct number of clusters (CNC)
is an important task in data clustering and has a critical effect on
nalizing the partitioning results. K-means is one of the popular
methods of clustering that requires CNC. Validity index methods
use an additional optimization procedure to estimate the CNC
for K-means. We propose an alternative validity index approach
denoted by k-minimizing Average Central Error (KMACE). ACE
is the average error between the true unavailable cluster center
and the estimated cluster center for each sample data. Kernel
K-MACE is kernel K-means that is equipped with an efficient
CNC estimator. In addition, kernel K-MACE includes the rst
automatically tuned procedure for choosing the Gaussian kernel
parameters. Simulation results for both synthetic and real data
show superiority of K-MACE and kernel K-MACE over the
conventional clustering methods not only in CNC estimation but
also in the partitioning procedure


## CITE:
S. Beheshti, E. Nidoy, and F. Rahman “K-MACE and Kernel K-MACE clustering”, to appear in IEEE Access, 2020.  


## How to use:
Use KMACE.m or Kernel_KMACE.m codes with data as input, to obtain the number of clusters as output
