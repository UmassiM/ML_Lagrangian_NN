Based on this paper ---> https://arxiv.org/abs/2003.04630
Lagrangian_NN is a project for the Advanced Machine Learning Course.\
It is a MLP which can learn arbitrary Lagrangians for any set of coordinates. It does so by taking generalised coordinates and guessing a functional form of L.\
Generalised accelerations are then calculated from it (using the chain rule on Euler-Lagrange equations) and compared to analytical solutions.\
The main advantage of learning L rather than a relationship between coordinates in phase space, is that symmetries of systems are automatically encoded
in the network regardless of the coordinate system fed to it. \
This means there need not to be data pre-porocessing, and no external rules have to be taught to the network to make it physically meaningful, 
leading to generalised predictability and stricter conservation of first integrals, which is not a granted features for other models.
