# Panorama-Registration-Stitching
Image Processing – Exercise 4

This exercise covers the following steps:
• Registration: The geometric transformation between each consecutive image pair is found by detecting Harris feature points, extracting their MOPS-like descriptors, matching these descriptors
between the pair and fitting a rigid transformation that agrees with a large set of inlier matches
using the RANSAC algorithm.
• Stitching: Combining strips from aligned images into a sequence of panoramas. Global motion will
be compensated, and the residual parallax, as well as other motions will become visible.
