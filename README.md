# tensor-mehods
Symmetric and Asymmetric tensor power iterations to estimate the parameters of the single topic model


Thoughts:
Robustness seemed to be a big problem associated with spectral methods; it seems like we can get "negative probabilities" (i.e. provable gurantees stated in terms of additive errors, and could thus for parameters for distributions like multinomial, we can have sum_i(p_i)=1 but some p_i negative) if we don't have enough samples, or if the moment tensor has a large magnitude of perturbation. 
