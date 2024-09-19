java c
EE7402   Statistical Signal Processing
Part I: Estimation Theory
Assignment
Q. 1.  Consider the observations
x[n] = A + w[n]    n = 0, 1, . . . , N - 1where  A is  an  unknown  constant  and  w[n]  is  a  sequence  of independent,  identi- cally distributed (IID) Gaussian random variables having a zero mean and a known variance σ 2 .
(a) To estimate the unknown parameter θ 1  = A, the following estimator
N-1

is proposed. Find a0 , . . . , aN -1  so that the estimator is unbiased and the vari- ance is minimized.  Show all the detailed steps involved.
(b) By using the optimal values of an’s obtained in part (a), ﬁnd the variance of
θ(ˆ)1 , denoted by  var (θ(ˆ)1 ).  What will happen to  var (θ(ˆ)1 ) as N → ∞?
(c) To estimate the unknown parameter θ2  = A2 , the following estimator

is proposed. Is the estimator θ(ˆ)2  unbiased? Is θ(ˆ)2  asymptotically unbiased?
Q. 2. Let x[n] (n = 0, 1, . . . , N — 1) be a sequence of IID Gaussian random variables having an unknown mean m and an unknown variance σ 2 .
(a) For the 2 × 1 vector parameter θ = [θ1  θ2]T  = [m σ2]T , derive the 2 × 2 Fisher information matrix I(θ) using the following formula

where E(·) is the expectation and ln p(x; θ) is the log-likelihood function. Show all the detailed steps involved.(b) Re-derive the same Fisher information matrix I(θ) using the following formula
Comment briefly on the computational complexity of the two methods used in
parts (a) and (b) for the derivation of the Fisher information matrix.(c) Based on the result of part (a) or (b), calculate the Cramer-Rao lower bound
for θ(^).
Q. 3. Consider the observations
x[n] = A + w[n]    n = 0, 1, . . . , N — 1
where A is the unknown parameter to be estimated and w[n] is zero mean noise.(a) Assume the noise samples are uncorrelated and let the noise variances be givenby σn(2)  = n + 1, for n = 0, 1, . . . , N — 1.  Find the BLUE of A and its variance.Examine what happens to the variance of the BLUE as N → ∞ .  Repeat for
σn(2) = (n + 1)2  and explain your results.
(b) Assume now that the noise samples are correlated with the covariance matrix

where jpj < 1 (p is known), σ 2  is a known constant, and N , the dimension of the matrix, is assumed to be even. Find the BL代 写EE7402 Statistical Signal Processing Part I: Estimation TheoryMatlab
代做程序编程语言UE of A and its variance.
Q. 4. Let the observed data x[n] be expressed as
x[n] = As[n] + w[n]   n = 0, 1, . . . , N — 1,where A is an unknown constant, s[n] is a known signal and w[n] is a sequence of IID Gaussian random variables having zero mean and an unknown variance σ 2 .  Findthe maximum likelihood estimators (MLEs)A(^)MLE ,^(σ)M(2)LE  for A and σ 2 , respectively.
Calculate E(^(σ)M(2)LE ), where E(·) is the expectation.  Is ^(σ)M(2)LE   unbiased?  Is ^(σ)M(2)LE
asymptotically unbiased?
Q. 5. Consider the linear model
∞ = Hθ + wwhere ∞ = [x[0] x[1] x[2]]T  is the 3 × 1 observation vector, θ = [θ1  θ2]T  is the 2 × 1 parameter vector to be estimated, w  is the 3 × 1 noise vector whose elements are white Gaussian variables with zero mean and variance σ 2 , and

is the known observation matrix, and E is a small number.(a) If ∞ = [2 2 2]T , ﬁnd the minimum unbiased variance (MUV) estimator θ(^) of θ
and describe what happens as E → 0.(b) If ∞ = [3 2 1]T , ﬁnd the MUV estimatorθ(^) of θ and describe what happens as
E → 0.
Q. 6. Consider the quadratic estimator
θ(^) = ax2 [0] + bx[0] + c
of a scalar parameter θ based on the single data sample x[0].
(a) Find the coefficients a,b,c that minimize the Baysian MSE.
(b) If x[0] ~ U [ —  ,  (uniform. distribution) and θ = sin(πx[0]), ﬁnd the LMMSE and the quadratic MMSE.


Q. 7. The data
x[n] = θ + w[n]    n = 0, 1, . . . , N — 1,
are observed.  The unknown parameter  θ is assumed to have the prior probability density function (PDF)
where λ > 0 is a known constant, and w[n] is a sequence of white Gaussian noise with zero mean and known variance σ 2  and is independent of θ .  Find the maximum
a posteriori (MAP) estimator θ(ˆ)MAP  of θ .
Q. 8.  (Open-end question) Do two or more of the following sub-questions:
(a) Describe one of your own research problems as a parameter estimation problem, with a reasonable model and some suggestions for a solution.
(b) Write some programs, say Matlab, to implement some of the parameter esti- mation methods you have learned.
(c) Study the research paper attached in this assignment.  Write a summary of the paper or part of the paper using your own language.






         
加QQ：99515681  WX：codinghelp
