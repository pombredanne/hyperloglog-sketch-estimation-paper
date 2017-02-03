# New cardinality estimation algorithms for HyperLogLog sketches
[Paper](http://oertl.github.io/hyperloglog-sketch-estimation-paper/paper/paper.pdf) about the estimation of cardinalities from HyperLogLog sketches.

## Abstract
This paper presents new methods to estimate the cardinalities of multisets recorded by HyperLogLog sketches. A theoretically motivated extension to the original estimator is presented that eliminates the bias for small and large cardinalities. Based on the maximum likelihood principle a second unbiased method is derived together with a robust and efficient numerical algorithm to calculate the estimate. The maximum likelihood approach can also be applied to more than a single HyperLogLog sketch. In particular, it is shown that it gives more precise cardinality estimates for union, intersection, or relative complements of two sets that are both represented by HyperLogLog sketches compared to the conventional technique using the inclusion-exclusion principle. All the new methods are demonstrated and verified by extensive simulations.
