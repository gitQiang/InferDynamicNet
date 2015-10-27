# InferDynamicNet
Using Gaussian Graphical Model(GGM) to find time-series networks rewiring. 
BrainSpan time periods data.

Inferring a network which "well" modeling chmorosome modification genes and RNA binding proteins in MICRF models.

Three main references:

1. inferring dynamic gene regulatory networks in cardiac differentiation through the integration of multi-dimensional data, 
--> main idea to penalty two continue time points.

2. Sharing and Specificity of Co-expression Networks across 35 Human Tissues, --> main idea to Gaussian Graphical Models and additional penalty.

3. FastGGM, main idea to give lambda and fast running

Tools for solving the GGM models: convex optimization model: 
1, use the similar idea with GNAT (ref.2).
2, use the matlab tools CVX http://cvxr.com/cvx/. (ref.1).


Prior information or result validation:
1, based on all the expression data to infer one density network as a prior network, or prior given zeros edges which would be decreasing the computational complexity.
2, use well-build database as prior networks, such as, COEXPRESdb and TS-CoExp

