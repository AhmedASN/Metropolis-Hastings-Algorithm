# Metropolis-Hastings-Algorithm
In statistics, the Metropolis–Hastings algorithm is a Markov chain Monte Carlo (MCMC) method for obtaining a sequence of random samples from a probability distribution from which direct sampling is difficult. This sequence can be used to approximate the distribution (e.g. to generate a histogram) or to compute an integral (e.g. an expected value). Metropolis–Hastings and other MCMC algorithms are generally used for sampling from multi-dimensional distributions, especially when the number of dimensions is high.
In a first application, where our Markow Chain is allowed to move only from a site to its neighbors (the local version), we will see how the chain get stuck in the wells.

![](https://github.com/AhmedASN/Metropolis-Hastings-Algorithm/blob/main/Images/the%20chain%20in%20the%20local%20version.png)

While in the second application, where the chain can go from its current site to any site with a given probability distribution ( global version ), we achieve our goal with a fast convergence ( see the comparaison below to the right ).

![](https://github.com/AhmedASN/Metropolis-Hastings-Algorithm/blob/main/Images/Chain%20in%20the%20global%20version.png)
![](https://github.com/AhmedASN/Metropolis-Hastings-Algorithm/blob/main/Images/glob%20and%20loc.png)
