# ver-cheb-sum-eval
Verified evaluation of finite Chebyshev expansions
=============================
This repository contains implementation of ten different algorithms for computing narrow enclosures for finite Chebyshev expansions of the form

$p(x) = \sum_{k=0}^n c_k T_k(x)$. 

While some of the algorithms are already known, the mathematics behind new algorithms is described in an accompanying preprient. 

The problem of computing enclosures for Chebyshev exapnsions arises in the context of ultra arithmetic, Chebyshev models, computer-assisted proofs of spherical t-designs, and automatic a posteriori forward error analysis of floating point algorithms for evaluation of Chebyshev expansions like the one in Chebfun/feval. 

Requirements
=============================

Beyond MATLAB, INTLAB V10.2 is needed to run the codes in this repository. INTLAB is a MATLAB toolbox for verified computations developed by Rump at the University of Hamburg. To run the examples provided in this repository, you also need Chebfun, a MATLAB package for numerical computing with functions developed at the University of Oxford.

License
=============================
See LICENSE.txt for licensing information.
