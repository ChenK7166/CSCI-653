# CSCI 653 Final Project

# Change Point Detection
The model is an unsupervised model to detect significant changes through high dimensional data over time series. For multiple change point detection, the model will recursively split the data into finer pieces and run the single detection model for each piece. Finally, a change point tree will be built.

# Performance Profiling
I will use **cProfile** to analyze python program and uses **VizTracer** to visualize the logfile.

# Parallelization
* Vectorization
* Trial change point predication
* Divide-and-conquer

# Example
VizTracer example (from Internet):  
![Alt Text](https://github.com/ChenK7166/CSCI-596-Final-Project/blob/main/Viztracer_example.png)

## Reference:
He Y, Rao A, Burghardt K, et al. Identifying Shifts in Collective Attention to Topics on Social Media[C]//International Conference on Social Computing, Behavioral-Cultural Modeling and Prediction and Behavior Representation in Modeling and Simulation. Springer, Cham, 2021: 224-234.

cProfile: <https://docs.python.org/3/library/profile.html>  
viztracer: <https://viztracer.readthedocs.io/en/latest/basic_usage.html>  

