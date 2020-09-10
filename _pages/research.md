---
layout: archive
title: "Research & Work Experience"
permalink: /research/
author_profile: true
---

## Scalable Solvers Group, Lawrence Berkeley National Laboratory 
<p align="center">
    <img src="https://crd.lbl.gov/assets/Uploads/_resampled/TopCroppedResize290205-strumpack-rotator.png">
</p>

Technical report of results can be found [here](https://ryansynk.github.io/files/technical_report_lbnl_ryansynk.pdf)

In the summer of 2019, I worked with Dr. Pieter Ghysels in the Scalable Solvers Group (SSG) at the Berkeley Lab. The SSG performs research in Numerical Linear Algebra to create better high performance computing applications for the DOE. My mentor and I worked on the Structured Matrices Package ([STRUMPACK](https://portal.nersc.gov/project/sparse/strumpack/)), a sparse direct linear solver that relied on a variant of the multifrontal method, but utilized Hierarchically Semiseperable (HSS) Matrices to compress larger fronts.

The application was parallelized, but only on CPUs. I worked on writing CUDA and C++ to create GPU parallelization. In the end, the code had up to a 3x speedup, and GPU programming is still part of the library today. I learned a lot working at the Berkeley Lab, and I got to write up my results in a technical report, which is posted above.

## NSF REU at Univ. of Maryland Computer Science Department

Git repository containing all the code can be found [here](https://github.com/ryansynk/adversarial-patch)

In the summer of 2018, I participated in an NSF funded REU at the UMD CS Department (check out the program website [here](https://www.cs.umd.edu/projects/reucaar/)). As part of the REU, I worked with a team of undergraduates under the direction of Prof. Tom Goldstein. We studied adversarial attacks on facial recognition neural networks. Specifically, we tried to develop an "adversarial patch" that could be physically printed and placed onto someones face in order to induce misclassification at test time.

As part of the project, I trained some neural networks using pytorch, and studied various different techniques for generating adversarial examples. While the group was able to get adversarial examples running ... the examples weren't robust to real-world applications. I was still proud of our results, since we were all underclassmen with no experience in machine learning!
