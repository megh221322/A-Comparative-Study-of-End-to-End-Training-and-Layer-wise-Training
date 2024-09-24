1 Layer-wise Training vs. End-to-End Training
The most common approach for training deep networks is using stochastic gradient descent end=to-
end and update all the parameters at the same time. We can imagine contrasting this approach
with training a deep network layer by layer using alternating minimization. This type of training
algorithm should have properties different from gradient descent (for example, a different implicit
bias other than the minimum norm). An interesting project would be to explore these properties.
Different questions that one could tackle are:
1. Can one get similar performance using layerwise training and SGD?
2. Compare the norms of the solutions obtained through layerwise training and SGD. Does
layerwise training find the minimum norm solution as well?
3. Is there a natural hierarchy to the complexity of the features learned in different layers during
layerwise training?

Dataset: MNIST
