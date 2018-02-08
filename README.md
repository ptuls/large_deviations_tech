# Preparing for the Worst: Applications of Stochastic Orders in Network Algorithmics

As of the present, unpublished manuscript on the application of stochastic orders in network algorithmics. Joint work with Jun Xu at GATech.

## Abstract 

> Performing operations on the traffic of high-speed networks face the typical problem of volume, velocity and variety. Network algorithmics is a field developed to deal with these problems. Of importance to network algorithmics is the in- puts/workloads into the solutions developed by the field are highly variable, and so is often modeled as a stochastic process. Moreover, a chief cornerstone of network algorithmics are randomized algorithms, which tradeoff a resource (for example, space) for a small, allowable error. Thus, it is crucial that one has to derive probabilistic guarantees on the performance of a solution with a worst-case workload under a performance metric (for instance, estimation error). This is usually achieved via probability bounds such as the famous Chernoff bound, but deriving such bounds for solutions from network algorithmics is often challenging.
>
> The derivation of these bounds can be dramatically simplified by exploiting a stochastic order, which is a notion of when one random variable is “larger” than another. In this paper, we survey some stochastic orders and show how they can be used to provide simple proofs of these bounds in the design of randomized algorithms in network algorithmics.

## Sidenote

This is supposed to be a sort of survey paper, but I can't help myself from coming up with new results. See, in particular, Theorem 21 for log-concave distributions and a nice connection with the [balls into bins](https://en.wikipedia.org/wiki/Balls_into_bins) model.
