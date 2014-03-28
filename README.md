# libtw

This was taken from [treewidth.com](http://www.treewidth.com).

## Abstract

There are many algorithms to compute an upperbound, a lowerbound or the exact treewidth of a graph. We have implemented a lot of upperbound and lowerbound heuristics and two exact algorithms (a Dynamic Programming and a Branch and Bound algorithm). This report compares the different kind of algorithms and shows that some algorithms are preferred. From our results with the lowerbound algorithms we can conclude that the Least-C variant for Maximum Minimum Degree almost dominates the other algorithms. For the upperbounds, we conclude that Greedy-FillIn is best. TreewidthDP is quite fast on most of the tested graphs, but runs out of memory on large graphs. If TreewidthDP can not run with the available amount of memory one could use QuickBB, which is slower, but uses less memory. We investigated the effects of the Memorization method on QuickBB suggested by Van Hoesel and found that it improved the algorithm with at least factor 15.
