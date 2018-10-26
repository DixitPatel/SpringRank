# SpringRank
Using SpringRank to find layer interdependence in a multi-layered network

############## Update 1 ##################

Currently working on Synthetic Spring Rank notebook
Need to redo the test part.

Questions/notes to self : 

The beta value is too low for synthetic network
Shall we preserve the edge weights while removing edges?


############## Update 2 ##################

Using trained ranks and beta values from network A gives a lesser sigma score (0.97) on test set of network A than for network B (sigma=1.0)
where sigma calculated by the equation : (1-sum(Aij-(Aij+Aji)xprediction(i,j)))
What is the expectation here ?
