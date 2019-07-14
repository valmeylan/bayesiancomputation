# Bayesian computation



MATH-435 Bayesian computation, lectured by Prof. Dehaene, is an EPFL graduate course.

This course aims at giving a broad overview of Bayesian inference, highlighting how the basic Bayesian paradigm proceeds, 
and the various methods that can be used to deal with the computational issues that plague it.

The assessment method was based on a programming project and its presentation.
It was asked to implement three methods presented in class, on a dataset of our choosing.

We had to apply these methods on three qualitatively different models.


### Bayesian inference on GARCH(1,1)

I performed a Bayesian inference on GARCH(1,1) models as my programming project.

• Python implementation of the MCMC Metropolis-Hastings algorithm for GARCH(1,1) models with (i) normal innovations ; (ii) student-t innovations.

• Interweaved (a) the Rejection Sampling and (b) the Importance Sampling algorithms for (iii) student-t data-augmented GARCH(1,1) model, see (D. Ardia, L. Hoogerheide, 2009).

• Algorithm tuning and cost highlights.
