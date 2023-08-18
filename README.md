# SCGMEL
The stochastic gradient descent (SGD) with computational graph approach is another machine learning approach that can be
used to optimize controller placement in SD-WAN. This approach involves constructing a computational graph that represents
the problem and then using stochastic gradient descent to optimize the objective function. The computational graph 
enables the use of automatic differentiation to compute the gradients of the objective function, which can be used to 
update the parameters of the optimization algorithm.
STOCHASTIC COMPUTATIONAL GRAPH WITH XGBoost for Controller Placement in SDWAN
The Controller Placement Problem (CPP) in SD-WAN has been addressed by a number of metaheuristic algorithms,
such as Multi-Objective Particle Swamp Optimization (MOPSO), Adapted Non-Dominated Sorting Genetic Algorithm III (ANSGA-III),
and Non-Dominated Sorting Genetic Algorithm II (NSGA-II). However, these algorithms, except for the ANSGA-III, were connected
with the problems of scalability, high computational complexity, and lack of intelligence in predicting the number of 
controllers. This study proposed a Stochastic Computational Graph Model with an Ensemble Learning (SCGMEL) approach to 
address the scalability, intelligence, and high computational complexity experienced by the existing algorithms.
The proposed SCGMEL used stochastic gradient descent with momentum and learning rate decay, a computational graph model, 
and the eXtreme Gradient Boosted Trees algorithm (XGBoost) as the optimization and machine learning approaches.
The proposed solution was tested using the datasets from Internet Zoo topology with six objective functions, namely 
load balancing, maximum controller failure, average controller-to-controller latency, average switch-to-controller latency,
and maximum controller-to-controller latency. The XGBoost model outperformed other regression models in predicting the number of
controllers, with a Mean Absolute Error (MAE) of 1.855751 versus 1.883536, 3.729863, and
3.829268 for the random forest, linear regression, and K-nearest neighbor, respectively. Furthermore, the 
execution time, average CPU usage, and total CPU usage of the algorithms demonstrated that the proposed SCGMEL is 
computationally efficient over the ANSGA-III, NSGA-II, and MOPSO with percentage decreases of 99.983, 
99.985, and 99.446, respectively. Consequently, the proposed SCGMEL was recommended over the reviewed
algorithms for controller placement in SD-WAN, subject to the usage conditions.

