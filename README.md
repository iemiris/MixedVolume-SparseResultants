Ioannis Z. Emiris, U.Athens (Greece) 2020

Software provided with no guarantee; users must mention this code, and refer to the relevant publications.


# Mixed Volume and Sparse Resultant

Software for computing Mixed Volume (via mixed subdivisions) and Sparse Resultant matrices
Software packages developed in the 1990's and 2000's, practically not maintained after 2002

incres.tgz is a tarfile of sources, executables, and library files for a standalone program (called Resin) and a software library for constructing sparse resultant matrices by the incremental algorithm of Emiris and Canny (JSC paper) and for reducing algebraic system solving to an eigenproblem, which is then solved by numerical linear algebra.

mixvol2020.tgz is a tarfile of the sources and executables for computing Mixed volume and Mixed cells via randomized mixed subidivions (by linear or affine liftings) on Linux. The Lift-Prune algorithm is due to Emiris and Canny (JSC article) and has been the most practical approach. The library also computes Stable Volume (see paper by Emiris and Verschelde).

maples.tgz contains several Maple routines for the above problems as well as files for converting between Maple format and input format to the C programs.

for more info see: http://cgi.di.uoa.gr/~emiris/soft_alg.html and http://cgi.di.uoa.gr/~emiris/soft_geo.html


Relevant Papers:
Emiris and Canny (JSC): https://www.sciencedirect.com/science/article/pii/S0747717185710413?via%3Dihub
Canny and Emiris (J. ACM 2000): https://dl.acm.org/doi/10.1145/337244.337247
Emiris and Verschelde (JSC): https://www.sciencedirect.com/science/article/pii/S0166218X99000037?via%3Dihub
Emiris (Tech. report on resultant code): https://arxiv.org/abs/1201.5810

