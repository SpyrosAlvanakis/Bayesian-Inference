# Bayesian-Inference

Consider the generalized linear regression problem defined by the following model: 
y=Θο+Θ1χ+Θ2χ^2+Θ3χ^3+Θ5χ^5+η
where η corresponds to white Gaussian noise and the components of the weight vector assume the following values: 
Θο=0.2 Θ1=-1 Θ2=0.9 Θ3=0.7 Θ5=-0.2

xi values in [0,2]
i in [1,N]

We encode our prior knowledge for the unknown parameter vector via a Gaussian distribution G(θ) with mean Θο equal to the true parameter vector 
in equation (1) and covariance matrix Σθ=σθ^2*Ι, σθ^2=0.1. Use the structure of the true model and perform full Bayesian Inference in order to evaluate y 
for 20 randomly selected test set points belonging to the interval [0,2] and for two different values of ση^2 (0.05 and 0.15). Plot your estimates and 
their errors on the (x,y) plane. 

Repeat experiment  using the following mean vector for G(θ): Θ=[-10.54, 0.465, 0.0087, -0.093,-0.004].Τ
With ση^2=0.05, perform the experiment four times, using two different values for σθ^2 (0.1 and 2) and two different values for Ν (20 and 500).
Comment on your results.
