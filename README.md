# Point-clustering-via-voting-maximization

Matlab Code: https://www.mathworks.com/matlabcentral/fileexchange/47544-point-clustering-via-voting-maximization

Implementation of CVR and CVR-LMV [1-2] methods for clustering.

The goal of the proposed methods is to cluster N given points into K clusters,
so that similarities between objects in the same group are high
while the similarities between objects in different groups are
low. The point similarity is defined by a voting measure that takes into account the point
distances. Using the voting formulation, the problem of clustering is reduced to the maximization
of the sum of votes between the points of the same cluster. It holds that the
resulting clustering based on voting maximization has advantages concerning the cluster’s
compactness, working well for clusters of different densities and/or sizes.

We will appreciate if you cite our papers [1-2] in your work:

[1] C. Panagiotakis, Point Clustering via Voting Maximization, Journal of Classification, vol. 32, no. 2, pp. 212-240, 2015.

[2] C. Panagiotakis and P. Fragopoulou, Voting Clustering and Key Points Selection,
International Conference on Computer Analysis of Images and Patterns, 2013
