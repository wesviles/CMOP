# CMOP###################
# CMOP-README.txt #
###################


### Data Availability: None ###

-The data analyzed and the results established are based on confidential patient information that is not presently publicly available.

-Sufficent statistics for simulation of random networks with density, degree distribution, and clustering coefficient along with edge weight distribution.


### Code Abstract: ###

-All functions are written in R (No packages required)

-CMOP-Base.R contains
	-Instructions for initializing the community detection procedure
	-Functions replicating Algorithms 1-3 in the Viles and O'Malley text.

-CMOP-Example.R contains
	-An example execution of constrained community detection.
	-An example for plotting community structure.

The functions provided produce the restults described in Viles and O'Malley text.  Specifically, there are two procedures (constrained and unconstrained) which are provided along with an example execution of the code.  All code is commented with all input parameters described.

### Code Description: ###

-Code (will be) available on GitHub
	-https://github.com/wesviles/CMOP/tree/version-1
	-Version 1

### Reproducability ###

-Verification that, on the synthetic data described in the CMOP-Base.R file,
	-the unconstrained procedure performs equally well to existing procedure
	-the minimum ICD volume per community constraint is satisfied.
	-the modularity of the constrained solution can not be increased by any constraint-satisfying single-vertex perturbation upon termination.






