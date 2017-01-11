# matrix-completion

This repository contains code for the article "Matrix Completion for the Independence Model" by Kaie Kubjas and Zvi Rosen.

Algorithm 2 of the paper is implemented in Sage code in "Completability.sws". This code determines completability, and in the 1 or 2 component case, it returns an explicit completion.

When the space of completions of a partial matrix is positive-dimensional, then one way to choose a completion is to optimize some function. The code in Maple to carry out this kind of computation with Lagrange techniques is in the file "Lagrange_multipliers".
