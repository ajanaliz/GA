# GA
using the famous Genetic Algorithm to solve a simple line alinement problem. learning different methods of problem solving through search

I worked on Binary GA and Permutation GA

notes on the Binary GA:
i used the Microbial GA to solve the problem domain

notes on the Permutation GA:
I used the Roulette wheel selection methods for the selection,
I used the Order One Crossover method for the Crossover
and i used the scramble Mutation for the Mutation.

Classes:
Point: a class to model a point in space
Dash: a class to model a line segment (dash)
Utility: a utility class that has several methods such as checking adjacency
and colinearity of two line segments, generating random numbers, randomising 
array contents and more.
Mutation: a class that has the implementation of four mutation methods
Permutation GA: the actual class where the GA is run.