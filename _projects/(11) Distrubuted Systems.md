---
name: Distributed Systems
tools: [OpenMPI, PThread, C++, Erlang]
image: ../assets/projects/11.jpg
description: Experimenting with multithreading and applications running in a distributed setting, thus making execution faster and handling fault tolerance.
---

# Distributed Systems

## Parallel Monte Carlo Simulation
A detailed analysis exploring different methods for generating random numbers in parallel and finding their application in common probabilistic algorithmic problems like Monte Carlo Simulations. Using 2 different methods for generating random numbers we have provided 4 ways to parallelize them and have successfully solved 2 math problems involving Monte Carlo Simulation. The time taken are analysed for different number of processes.
<p>{% include elements/button.html link="https://github.com/tanuj208/Distributed_Systems_Project" text="View Code" %}</p>

## Parallel Service Simulator
An implementation of a parallel simulation of real life scenarios using pthread. As a part of an assignment, this implementation serves to be an accurate method to learn about parallel processing and the use of pthreads to achieve so. Using pthreads the simulation of 2 services : Cab Hailing App Service and Biriyani Service, has been done where where different entities like Driver, Rider, Payment Server or Chefs, Tables and Students run independently using threads and interact with each in a distributed setting.

<p>{% include elements/button.html link="https://github.com/mayankmusaddi/Parallel-Simulator" text="View Code" %}</p>

## Parallel Implemenetation of Different Algorithms
Parallel implementation of Quicksort, Mergesort and Bellman Ford using C++ MPI, C Pthreads, JAVA RMI and Erlang.
<p>{% include elements/button.html link="https://github.com/mayankmusaddi/Parallel-Sorting-Algorithms" text="View Code" %}</p>