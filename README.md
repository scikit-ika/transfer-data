# transfer-data
Test data for the transfer learning module.

# Bike
Real-world datasets obtained from [here](https://www.cs.bham.ac.uk/~minkull/publications/DuICDM2020.pdf). 

# Fashion MNIST
* Semi real-world dataset.
* The original MNIST\footnote{\url{http://yann.lecun.com/exdb/mnist/}} and Fashion MNIST\footnote{\url{https://github.com/zalandoresearch/fashion-mnist}} datasets are used as the source stream, and the target stream is generated with varying similarities by inverting all pixel values of v% of the classes. We denote these configurations as MNIST v% or Fashion MNIST v%, where v% indicates the dissimilarity between the domains. In addition, we apply a 2 by 2 filter on both MNIST and Fashion MNIST datasets for reasonable performance outputs from the random forest base learners with limited tree models.
