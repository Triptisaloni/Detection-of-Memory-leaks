# Detection-of-Memory-leaks

3.Detection of Memory Leaks in C/C++ via Machine Learning


Summary:

Memory Leaks

Primary reason for software aging
It is memory fragment which is not freed, even if it is never accessed again
Types:- Unreachable and Reachable

Approach[ Detection ]

Gen Count - tells that in how many previous generation a particular site has created objects which are not disposed still in current generation
Data Collection - Wrapper function are used to sieze event data when an allocation or de-allocation function is called
Leak Detection - A Classifier is trained to differentiate between leaky and non leakysites

Evaluation 

Accuracy of leak detection
Performance Overhead
Feature Visualization

Techniques

Static Analysis
Dynamic Analysis
Software Rejuvenation

Future Works

To lower the instrumentation overhead by sampling and by online aggregation of the events
