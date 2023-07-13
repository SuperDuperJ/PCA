# PCA

This notebook is the self-assigned final project for a Coursera course that I took entitled *Mathematics for Machine Learning: PCA* during the Spring 2023 term.  
In an effort to digest the material learned in this course and expand upon it, I decided to write this work.

With the exception of the first and last four code blocks, the work is entirely my own.  
Most of the functions herein were assigned in the aforementioned course, except for the reconstructError, compEquiv1, and compEquiv2 functions.  
These functions display my penchant for vectorization.

The intention of this notebook and the course is to give intuition on PCA.  
The PCA algorithm herein is by no means the most efficient or versatile PCA algorithm.  
This is because it does not use the SVD to reduce the data to its most salient components and instead embeds the data in a lower-dimensional subspace.  
For a robust PCA algorithm, consider the Sci-Kit Learn PCA algorithm.
